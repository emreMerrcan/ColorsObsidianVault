---
tür: oyun-tasarımı
proje: "[[NERRATIVE SYSTEM]]"
durum: taslak
kaynak: "RulebookPDFS/annie-spratt-6a3nqQ1YwBw-unsplashs.pdf"
tags:
  - ttrpg
  - sistem-tasarımı
  - kural
---

> [!claude] Claude · 2026-10-24
> Eski rulebook'un ATTRIBUTES / SKILLS sayfası. Aşağıdaki metin Pixlr dosyasının (`annie-spratt-6a3nqQ1YwBw-unsplash6.pxz`) text layer'larından script ile **birebir** kopyalandı. Yazımlar, boşluklar ve noktalama orijinaldeki gibi. Layer başlıkları markdown başlığına, yan yana duran sütunlar tabloya çevrildi; dekoratif alt çizgi layer'ları alınmadı. Markdown'ın yutacağı karakterlerin (`*`, `~~`, satır başı `---`) önüne görünmez `\` kondu, ekranda orijinal gibi görünür. Süreç: [[Rulebook Aktarım Takibi]].
>
> Skill tablosu: 1. sütun skill, 2. sütun büyük yazılmış bağlı stat, 3. sütun altındaki küçük gri ikinci stat, 4. sütun açıklama (sayfadaki sırayla).
>
> **Güncel sistemle ilişkisi:** zar ve attribute'lar [[NERRATIVE SYSTEM#Stats]] (d10, -10…+10), türetilmiş statlar [[NERRATIVE SYSTEM#Attributes]], skill listesi [[NERRATIVE SYSTEM#New Skills]], skill limiti [[NERRATIVE SYSTEM#Skills]] (burada 4 slot, güncelde max 2). Hepsi çelişki tablosunda zaten var.
>
> ![[Rulebook - Attributes ve Skills.jpg|600]]

## ATTRIBUTES

|  |  |
|---|---|
| STRENGTH | :: 2d10 + 20 |
| AGILITY | :: 2d10 + 20 |
| TOUGHNESS | :: 2d10 + 20 |
| INTELLIGENCE | :: 2d10 + 20 |
| CHARISMA | :: 2d10 + 20 |
| WILL | :: 2d10 + 20 |

|  |  |
|---|---|
| HEALTH | ::  SB + TBx2 + WB |
| ENDURANCE | ::  Same as health |
| RESISTENCE | ::  Calculated from armor + Natural Skin |
| PACE | ::  10 |
| MOVEMENT | ::  Agility Bonus \* 2 |
| ESSENCE | ::  Focus Level + WPB + Race Essence |

### PASSIVE STATUS CHECKS

When you stay idly, and an enemy does something that requires a check of your passive status, you apply extra difficulty to their roll.  Passive Statuses are your normal stat bonuses - 2.

Strength : Passive stiffness, rediness on taking action.
Agility : Reflexes.
Toughness : Physical integrity, sturdiness.
Inteligence : Perception, mental track of events and environment.
Charisma : Soical awareness, composure and gut feeling.
Will : Spiritual composure, overall drive and vision.

Let' Lets say you have 45 INT. Soembody trying to sneak around you would get -2SL to their roll.  Someone trying to break your bone while you're dazed out must take your THG Passive Status to their Strength roll. If somebodys trying to charm you by lying, they have to pass your passive charisma. If a spell taking you into their will, passive WP. If somebodys trying to push you, they must pass passive STR. Lastly, if they try to catch you off guard, WHILE you're looking at them, show your reflex with your passive AGL.

## SKILLS

You have 4 skill slots for each level of skill, meaning you can only have 4 skills on the same level at a time. If you have 4, 1 level skills, you have to level one up to open room.

|  |  |  |  |
|---|---|---|---|
| Acrobatics | AGL | STR | Elaborate physical actions like rolling, backflipping or walking on a thin rope. |
| Animal Care | CHR | INT | Mastery for caring, reading, communicating and training animals. |
| Athletics | STR | AGL | Physical prowess, ability to muscle, push, jump and wrestle. |
| Swiftness | AGL | STR | Physical quickness, actions of pace and speed. Run, climb and outpace. |
| Balistic Skill | AGL | STR | Capability and accuracy with ranged weapons. |
| Weapon Skill | STR | AGL | Mastery and capability of wielding close combat weapons. |
| Expression | CHR | INT | Clearness of expression, persuation and agreeableness by words or manners. |
| Deception | CHR | AGL | Mastery over hiding the truth. Telling lies, giving false leads and trickery. |
| Healing | INT | WP | Caring for wounds or diesases and general knowledge of ones body. |
| Instincts | WP | THG | Mastery of intuition, the inner voice, the gut feeling for a threat or an appeal. |
| Mount | AGL | STR | Mastery over riding a beast, a vehicle or anything you can sit and direct on top. |
| Stealth | AGL | CHR | Mastery over staying unnoticed, sticking to shadows or hiding ones intentions. |
| Slight of Hand | AGL | INT | Fast hands, lockpicking, tying, playing an instrument or knitting., snatching between blinks. |
| Fortitude | THG | WP | Sturdiness of body, soaking hits, withstanding physical hardships. |
| Scholar | INT | CHR | Level of knowledge over studied subjects, how the world works and it's cultures. |
| Survival | INT | THG | Mastery of survival in an environment and against its inhabitants. |
| Cognition | INT | CHR | Quick thinking, common sense, understanding, reasoning, problem solving. |
| Investigation | INT | CHR | Searching and finding hidden details. Leading tracks, making sense of scenes. |
| Focus | WP | THG | Level of wholeness in sprit, intuition and control over ones own being. |

> [!claude] Claude · 2026-10-24
> **⚠️ Dikkat çeken yerler** (düzeltilmedi, karar senin)
> - Gri ikinci-stat sütunu sayfada **iki kez** var: 19 satırlık layer'ın üstüne, son 9 satırı (Mount → Focus) tekrar eden ikinci bir layer binmiş. Değerler aynı, bir kere alındı. Görselde o satırlar kalın/çift görünüyorsa sebebi bu.
> - d100 dönemi: attribute'lar `2d10 + 20`, örnekteki "45 INT → -2SL". [[NERRATIVE SYSTEM#Stats]] d10'a geçti.
> - Türetilmiş statlar ırk sayfalarındaki ve [[Karakter Açılışı]] tablosundaki formüllerle de tutmuyor (HP burada `SB + TBx2 + WB`, ırk sayfalarında `S+2T`, `S+3T+W` gibi ırka göre değişiyor; PACE burada sabit 10).
