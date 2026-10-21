I want you to make me a character controller script(s).  
-A 2.5D character controller that moves a 3D model of a character, playing its animations.  
-Uses the new input system, OnMove with 4 vector values, OnCrouch with button toggle, OnRun with button toggle, OnFlashlight with button toggle, OnHeal with button holding and OnInteract with single press value.  
-Moving has 3 modes as mentioned, crouching, walking and running. The character moves by gaining acceleration, and the rates of accelaration and decaleration are adjustable on inspector, as well as different speed caps. Any speed higher then the cap causes decelaration.  
-Flashlight will be toggling a light emitter object. Also it will have a cone shaped collider and the entities within them, if they have the right tags and if they're on the direct line of sight of the light source (no other object in between) they will be inflicted the light effects (this will be handled on the opposit side, here will only say "youre lit!")  
-The character has 30 lives, and they're divided into 3 sections with each 10 health. If not taken damage for a while, regeneration starts, but only up to the limit of the current section. So if the health is 15, it will only regenerate on its own till 20.  
-OnHeal starts a healing process and forces a crouch. If held for a while, the healing concludes and the player heals 11 health.  
-Interactable objects have trigger zones. If the player calls OnInteract while within one of those zones, an interaction request starts with that object. But every interaction can be unique to the type of thing, so no deep implementation for now, simply throw a debug for now.  
-Almost all parameters should be adjustable on the inspector.  
  
-There's also a sound-attention system. Some interactions, actions and movements can cause sound areas that attract enemies or interact with other stuff. To simply put, there will be a circle drawn, size decided by the magnitude of the source, at the source, and everything in the circle that is susceptible to sound reacts how they see fit.  
-For the player, OnHeal creates a huge sound zone every second. Walking and runing creates aswell every step (every second). And flashlight toggling creates a small one.  

A system for light and dark:  
There needs to be a system to grade which areas are lit and which areas are in the dark. Since the light is dynamic, and lightsources can be moved, the game has to update them also.  
  
First enemy Slughound  
They have 3 modes  
-Passive search. It is periodically given a poisition that the player have been, goes there and roams around.  
-Active search. If currently within the visinity of the player (within a circle), it recognises that and does a more active search, vaguely homing towards the players position.  
-Chase. The player is deteceted. And now the slughound runs and attacks to kill the player.  
  
-Movement: It moves contuniously on passive search. On Active search, it moves, stops then moves again with changing time period ranges. Then on Chase, it rotates to the player and locks on to the angle. After a small indication gap, it lunges with great speed, decelerating as it slides on the ground. As it stops, It rotates to the players last seen location and repeats.  
-Players position memory: When the hound gets an update on where the player is, it locks onto that position to try to get there. Lets say they saw the player through a window, and as they were pathfinding around the player changed position. They would still be aiming to the last point they saw the player at, essentially a PlayerGhost system should be developed, so the enemies can track their last knowledge of the position.  
-Sensitivities: Receiving sound from any source causes the PlayerGhost to appear close to the actual source (this can be caused by sources other then the player btw). They can also see light. If they get "lit" by the flashlight they instantly agro to the player. They have a cone of sight area on the front and although when the player is in direct line of sight and in the zone, if they're in a certain level of darkness, the hound cannot see them. Any presence of light however allows them to see the player.  
-Blindness: If the hound is lit by the flashlight (or a light source deemed blinding) within a certain closeness to the player, they get blinded and their view zone gets blocked for a couple seconds.  
-Shredding: If the player ever collides with their mouth, a shredding sequence starts, as the monster plays an animation, the players position gets anchored to their mouth assets position. After dealing 10 damage, the player is thrown at a random direction with high velocity. After landing they regain movement input control again and the monster lunges again.  
-Pathfinding:  
  
  
Second enemy Darkmite  
-DarkmiteEmitter: These are zone definers placed on the map. As the player comes to proximity, they spawn a bunch of darkmites and if they get far they despawn (performance)  
-Giggles: They occasionaly play a giggling sound, rarely.  
-Behaviour: Darkmites DO NOT get out of dark areas. If the player steps into the dark, they slowly start walking towards them. On contact with the player they deal damage every second. They keep doing so till the player dies or they get lit.  
-Courage: Darkmites have a courage counter. They start with 50 out of 100 courage. And every second the player is in the dark and they get close to them, the courage meter rises, and every attack increases the courage of all the Darkmites. The courage meter directly rules their movement. When they get lit by a light source, they start losing courage incredibly fast. If the courage fades, the darkmites starts rushing back into the dark, hiding.  
-Movement: When the players within their zone, all of them get notified of that and start their movement towards them. It is a simple find the closest route pathfinding. And on running away from the light, they find the nearest unobscured dark spot on the world and run there.  
-Burning: If a darkmite gets exposed to light for a while, they die.