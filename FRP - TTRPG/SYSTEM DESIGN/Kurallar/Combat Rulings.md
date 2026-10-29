---
tür: oyun-tasarımı
proje: "[[NERRATIVE SYSTEM]]"
durum: taslak
kaynak: "RulebookPDFS/annie-spratt-6a3nqQ1YwBw-unsplash.pdf"
tags:
  - ttrpg
  - sistem-tasarımı
  - kural
  - combat
---

> [!claude] Claude · 2026-10-24
> Eski rulebook'un COMBAT RULINGS sayfası. Aşağıdaki metin Pixlr dosyasının (`Combat Rulings.pxz`) text layer'larından script ile **birebir** kopyalandı. Yazımlar, boşluklar ve noktalama orijinaldeki gibi. Layer başlıkları markdown başlığına, yan yana duran sütunlar tabloya çevrildi; dekoratif alt çizgi layer'ları alınmadı. Markdown'ın yutacağı karakterlerin (`*`, `~~`, satır başı `---`) önüne görünmez `\` kondu, ekranda orijinal gibi görünür. Süreç: [[Rulebook Aktarım Takibi]].
>
> Sayfa üç sütun; burada soldan sağa, her sütun yukarıdan aşağı okundu. Success Level ölçeği hizalı olduğu için kod bloğunda: sayfada yeşil `+2SL +1SL +0SL / Success` ile kırmızı `-0SL -1SL -2SL` aynı satırda yan yana duruyor.
>
> **Güncel sistemle ilişkisi:** SL hesabı [[NERRATIVE SYSTEM#Stats]], Pace [[NERRATIVE SYSTEM#Pace]]. Yarım aksiyonlar ve silah özellikleri: [[Combat Specials]].
>
> ![[Rulebook - Combat Rulings.jpg|600]]

# COMBAT RULINGS

## Steps of Combat

### 1 - Decide Initiative

Initiative is rolled to create who goes first in the turn based system. Usually the one that decides to go in first gets the Initiative first. The GM decides which stat will be at test. If the situation requires fast reactions, Agilitys is rolled. Or maybe the fight starts before heavy social clues, Charisma or Intelligence may be asked. Check Initiative part to see more.

### 2- Start your turn with choosing your action and a target.

You decide on an action and someone to use it on. If you are attacking, then you may also pick a target body part. Check Targeted Hit Locations table to see your targeting advantages. Otherwise its decided on the Random Hit Locations table. 

### 3- The DM gives a Difficulty Number.

Based on your action, target and depending on some additional conditions, the GM gives a Difficulty Number for you to pass and which stats and skills you should roll for the test. 

If an Opposing Test is created, the GM mentions the opposing reaction and rolls for it too. Check Opposing Test part.

### 4-  Checking the for doubles and SL's

Calculate your SL to see if you passed the Difficulty Number or Opposing Test. 

Also check for doubles. If your dice meet the conditions for Critical Hits & Fumbles. Apply them. 

### 5- Apply the effects.

You calculate the effects of your action. Calculating damage etc.
Then GM describes the result and how things take place in the world.

### 6- End of turn.

Wait for your turn and repeat the cycle. If you have already finished your turn, you cant react to somebody else with an opposing test.

## Calculating Damage

Every kind of damage and weapon has a given damage value for them.  Lets check for a successful Long Sword hit. The long sword has the damage of 2SL+4. So the damage is calculates with Success Level of my test, lets say I rolled 3SL, inserting that to the equation, damage is 3x2+4 = 10.

If I crit, then the SL (in this case 3) gets doubled to end up dealing 16 damage.

Then this damage gets reduced by the enemies local resistance. If an enemy is wearing a chestplate that has 6res, then my damage applies as, 16-6 = 10

## Random Hit Locations

If you dont mention where you target, the Random Hit Location table will decide for you. Its decided by reversing the numbers on your d100 roll, like if you rolled a 31 on your test, then it will be 13 on the Random Hit Location Table.
For pacing, ignore this unless nececcarry and calculate armor based on a single rough resistence value for each character.

| Rolls | Locations |
|---|---|
| 1 - 10 | Head |
| 11 - 28 | Left Arm |
| 29 - 45 | Right Arm |
| 46 - 80 | Body |
| 81 - 90 | Left Leg |
| 91 - 00 | Right Leg |

## Action

An action is anything you asked to roll for. In combat, there are obvious time limitations so you can, at default, have 1 action at a time. Minor actions like drinking water, pushing a medium sized object or hitting a sleeping person, may not even qualify to have a test.

## Opposing Tests

If your action clashes with the action of anther being, you two roll an opposing test to see who succeeds. Say if you try to hit someone but they are trying to dodge you. You will roll for Weapon Skill while they are rolling Agility to dodge. Who's SL is higher succeeds. If both parties fail, non gets anything. If both succeeds but one has higher SL, then they both have their way while the better one landing their action anyways.

## Flanking & Disabilities

Flanking an opponent in close combat causes you to gain  +20 by each ally flanking. If youre 3 people ganging up on 1 person, you all gain +40. If you flank 3 to 2, you all gain +20.

The environment, the surface you fight on or the very weather can cause disadvantages sometimes. Wound, surface, weather or enemy conditions can cause this.

## Movement

MOVE amount of meter is your running distance per turn. MOVE/2 is your avarage walk speed. You can take one free Move Action every turn. After that, you can spend all your Action Pace to take another Move Action. (Also check half actions for dashes and jumps). You can never naturally go beyond MOVE\*2 meters on a single turn. If two people run to outpace eachother, their MOV stat adds as a bonus to their opposing rolls. 

Move Action: Once for free but costs all pace on second use.

Running : Traverse Mov meters
Flying :      Fly for Mov \* 2 meters
Crawling : Traverse Mov / 4 meters
Climbing : Traverse Mov / 8 meters

Jumping: Can leap for STR/2 or AGL/2 amount of meters in length and height

## Critical Hits & Fumbles

If the tens and decimals of a dice you roll are thats called a double. Like rolling 22, 66 or 100. If the roll failed, it now a critically failure, if it succseeded, its a now critical success because of the double. If its a critical sucsess, double the SL of your success. But if you critically fail while attacking, your weapon may fly out of your hand, or you can tackle and fall.

## Concentration

You concentrate and use no movement or take no other actions for the round. After spending an un-interrupted turn, you get +3SL to your next move next turn.

## Pace

While taking an action, you spend Pace. If your last action exceeds the Pace limit, you get -30 disadvantage for each exceeded point of pace, on that last action.

- Weapon attacks depend on Attack Pace of the weapon
- Half-Actions take 2 Pace (every consecutive half action gets +1 Pace cost)
- By spending all Pace, you can run again
- Simple bodily actions may take 1 Pace
- GM can assign Pace values to various actions

ALSO: Dual Wielding gives +2 Pace on using that item

PACE BORROWING
You can extend an action to your next turn. Like when you have 2 pace left and it takes 4 pace to reload your weapon, you can say I will be reloading. Next turn, you will use 2 more pace and be done with the action. You need to not get interrupted in the meantime.

## Targeted Hit Locations

If you target a specific location, your attack will be harder to hit. Each body part has a corresponding SL threshold you must pass to land them. 

Hitting the target can have amplified effects based on intention

| SL's | Locations |
|---|---|
| -3 SL | Head |
| -2 SL | Arms |
| -1 SL | Body |
| -2 SL | Legs |

## Success Level

The GM asks for a Difficulty Number you should surpass. Success Level gets calculated by counting the 10's of how much you passed your own stat. Like lets say I have 50 as my stat. If I roll 30 as a result, my Success Level will be 2. (50 - 30 = 20 so 2SL)  If a Difficulty Number is given like 2, then my SL have to pass that to succeed.

Lets say my stat is 53. My roll would give the SL of:

```
-20           -10             0              10             20 
33             43            53            63             73
-------------------------------------------------------------
+2SL       +1SL       +0SL            
Success
-0SL           -1SL        -2SL
```

## Initiative

At the start of the combat every participant rolls initiative and take their turn one by one. If an opposing action takes place, your two turns gets linked despite the initiative order, you two use your opposing actions at once. Non-opposing actions should wait for their own turn.

Or, for a planned strike, players can divide themselves in order, maybe even pairs of two. DM can also order enemies like that for simplicity.

## Falling & Bleeding & Burning & Stun & Grapple Etc.

Any fall higher then AGB or THB meters starts dealing 4 damage per meter. If you arent falling properly (unconcious or thrown) get 6 per meter instead.

Multiple instances of bleeding can stack. Bleeding causes you to take 1 damage each turn, reducing itself by 1. Some wounds inflict limitless bleeding until taken care of. 

Burning: It will grow indefinitely by +1 until its put out. You take burning unit of damage every turn, and its starting unit will be given. Burning will be reduced by your action SL+2 to put it out.

Stagger: Every unit of stagger adds -1SL to all rolls, gives -2 Pace and -1 MOV. Stagger gets depleated by 2 each turn.

Stunned: You cant take any actions, reactions nor move.

While grappled or ensnared you can roll for a stat check. If you pass the DN given by the stun, you get released  or take control over the enemy in similiar fashion (normal grapples takes your SB for save DN)

Poison and Savable Conditions: Some conditions only gets inflicted when you fail a stat check with a given DN. Some may need multiple save rolls for a more average result. Some of them get reduced effects by your SL on that check. For example, poison that has 3 DN needs you to have 3 or less SL to take its effect. 

Exhaustion: Same logic with Stagger, only its cleared by resting and increases slowly overtime. Avoiding sleep, high tempo adventures, sickness or low essence can cause this to add up.

## Stealth Attacks

A stealth attack is gives a surprise raunt to the team if used to start the combat. A stealth attack, if succeeds, is automatically a ciritcal hit. If the enemy knows your general position in mind you cant stealth them. Hide and change position. Unforseen and unseen attacks counts as stealth attacks. A player can also fake an action in plain sight with deception to get a stealth attack. You may take the enemies Passive Intelligence as disadvantage on your Stealth rolls. And if they already see you and you're doing a fake out, they give disadvantage with AGL or CHR Passives.

## Wounds & Fractures

A casual fight ends when the endurance hits zero, roll a saving throw with WPorTH+20 test to not flee or knocked unconcious. But in life and death situations, you will get +50 on these rolls.

Each time you get damaged on your health, you also roll on the Lingering Injuries table. When you hit 0 health, also make another save roll not fall to crawling condition. When your health is below zero, get -10 disadvantage on your actions and getting damaged makes you roll for Critical Fractures. If you hit the negative equal of your health, you die.

## Crawling Condition

If you hit 0 health you fall to the ground. Can only move around crawling. Each turn you get a point of Revivify. 2 points can be spent to take an action or 5 can be spent to stand up on yourself with TB endurance.

Until you get incapacitated or hit negative amount of your normal health, you can stay in crawling condition.

> [!claude] Claude · 2026-10-24
> Aşağıdaki **Momentum Actions** bölümü sayfanın sağ kenarından taşıyor (x=1858–2455, sayfa 1920 px genişliğinde), yani PDF'te görünmüyor ya da kesik. .pxz'de tamamı var.

## Momentum Actions

If a player rolls above 5SL for an action for the first time, they can get a free Half Action. This action must be chained to the first one within reason and happen right after.

> [!claude] Claude · 2026-10-24
> **⚠️ Dikkat çeken yerler** (düzeltilmedi, karar senin)
> - **Momentum Actions** PDF'te görünmüyor (yukarıda).
> - "Wounds & Fractures" bir **Lingering Injuries** tablosuna ve **Critical Fractures**'a atıf yapıyor; bu tablolar hiçbir sayfada yok ([[Roll Tables]]'ta da yok).
> - d100 kalıntıları: SL = geçtiğin her 10, doubles (22, 66, 100), Flanking +20/+40, Pace aşımı -30, hit location için d100'ü ters çevirme, Wounds'ta +20/+50/-10. Güncel d10 sistemine çevrilmesi lazım.
> - Dual Wielding üç yerde üç farklı: burada "+2 Pace on using that item" (maliyet mi?), [[Combat Specials]]'ta "+10 to extra actions", [[Arik'Xea]]'daki Ambidextrous "Get +2 Pace while dual wielding" (kazanç mı?).
> - Critical Hits metninde bir kelime eksik gibi: "If the tens and decimals of a dice you roll are thats called a double".
> - Movement'ta MOVE çarpanları (Flying x2, Crawling /4, Climbing /8) [[Attributes ve Skills]]'teki "MOVEMENT :: Agility Bonus * 2" ile birlikte okunmalı; güncel MOV: AGLB ([[NERRATIVE SYSTEM#Attributes]]).
