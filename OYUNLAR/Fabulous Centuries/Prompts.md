


Action creation steps:

Action type (passive, move, turnly, trigger)

Trigger (if null, can simply activate. if yes, select an event call to listen to and CAN ask further questions about that event call. Like if I picked OnHit, can also pick (Receiver inferior, Attacker is Ally on my row, the attack damage is more then 2))

Targeting: Automatic or selecting. Automatic allows you to set position or status checks for determining avalible targets. Automatic picks a viable target and apllies the action directly. If Selecting is activated, the game allows the player to pick a target that fits selection checks, like; Whole table (everybodys pickable), Enemy table (enemy cards pickable), enemies lower then 3 that has Human card type (only they are pickable). We add targeting type and add as many checks as we want to that targeting limitation.

Checks: Can set up checks for positioning or card statuses (attribues, keywords, conditions etc.).  Like if theres an enemy on forward slot, thats it. Or maybe like, if an enemy is under 3 health. Or both. The checks can be asking for almost anything.
From: The actor of the action (some actions can make others attack etc. Multiple actors can be added)

What: What does the action do. This is where we add the Command into that action.

And (+command, adding other steps so on the conclusion of the first one, second one fires. Add a toggle so that the second step can fire even if the first one is cancelled)


Let's say I want a card that makes its allies hit trigger their attacks once again on the turn and then heals themselves for the amount of damage accumulated as a Move.

Type: Move
Trigger: None
Targeting: Allies on row, Check for if they have Turnly
What: cmd_rallyAlliesForTurnAttack
+
And:
Type: Trigger
Trigger: OnAllyHit AND InActionThread
Targeting: Self
What: cmd_healForDamageAmount

(action thread mentioning one contunious action chain. When the action of this card returns complete, the thread closes and if there are lingering or ractive events going on, they remain outside of that "thread")

For better creating the action system, i will give you a couple card examples so you can tweak it better.

Unit examples:
Assault Footmen: Turnly: Hit the enemy in front of you by 1. Passive: On an ally from eighter of your sides hitting an enemy that is 1 in front of them, also hit that enemy for 1.

Shepherd: Turnly: If i can scare the enemy in front of me (their health being lower then my Fearsome Condition level), Eat (execute) them. Move: Play the last Eaten enemy as an ally.

Trickster: On Play: I steal an enemies Support (extra health) and add to myself. Move: I select an enemy that is set to take an action, and route it to myself to be the target of it.

Ashen Warrior: Passive: All my allies that are type Corpse do also inflict Bleed on hit. If an enemy dies and they were bleeding, take that enemy, fully heal them, give them Weakness and play as an ally. Turnly: Inflict bleeding to the 3 row slots in front of me.

The Overseer: OnPlay: Pick an adjacent deck. Passive: Can draw an additional card every turn. Move: Draw 2 Special cards from a deck and chose 1 to keep. (on death the deck access is gone)

Connected Roots: Passive: I get connected to my adjacent allies. If a connected ally gets healed, I also get +1. Turnly: Heal a connected ally. Move: Choose one of my conditions, and copy it to all of my connections.

Event Cards:
Organ Shifter: OnPlay: Choose two allies. 2 conditions and the Turnly ability of the first ally are now copied to the second one (second cannot previously have a Turnly).

Taming Whip: OnPlay: Hit an enemy for 2, +2 damage if they are type Animal or Monster and stun them for 1 turn. If they die before the stun runs out, play a Tamed Mount from them.

Shimmering Light: OnPlay: For this turn, all enemies have 2 less health, to the minimum of 1 health. (temporary)

Healing Flowers: OnPlay: Select an ally, and heal them for +3 health. Then heal every rowmate by +1.

Augment:
Supporting Spirit: Passive: When the first time in a turn the Host takes support (excess heal), I also give the Host +1 points.

Posion Spores: Passive: The host also inflicts Poison on hit. OnDeath: (the death of the host) Inflict 2 posion to all adjacent slots. If anybody die from that posion, Play a copy of me.

Thundering Fists: Passive: The hits of the Host also push the enemy 1 slot backwards. If they cant move back, then deal 1 damage to the card behind them.

Tamed Mount: OnPlay: The subject enemy dies, and their conditions, reserve 2 health and Move ability are copied onto me. Select an ally as a Host to use my abilities and conditions, and heal them.

Hazard:
Seaways: OnPlay: Select a slot and apply effect on the entire row of that slot. Allies on those slots can move one additional time but only sideways.

Zone of Darkness: OnPlay: Select a slot and also effect 2 sides of that slot (3 slots in total). Units on those rows are silenced.

Blessed Steps: OnPlay: Select a slot and effect right, forward and rightforward diagonal of that slot also (creating a square). The first time an ally steps into the blessed slots, they get +1 health and +2 temporary health.

Rockslide: OnPlay: Select a slot and also effect 2 sides of that slot (3 slots in total). The slots are considered occupied, so units cannot walk through them.

Dream Card:
Monster God: Passive: Gain +1 spark on every enemy death. OnSpark (10): Play a Ravager God on the table and reset the sparks.

Day of Heaven: Passive: On playing an ally, take 1 health from them and gain 1 spark. On reaching 10 sparks, give +1 healing to the 5 lowest health allies on the table.

Wilderness Call: Passive: If you skip playing a card, blind draw and play a card from the Animals Deck instead.

Totem of Immortality: Passive: On an ally death, they gain Imaginary (makes the card disappear the next turn) condition instead.