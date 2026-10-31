Both Attributes and Skill have an origin point and any increase over the origin point causes a decrease on another stat to go under it. If the origin point is 5 and I want to increase a stat from 7 to 8, I have to decrease another by 1.

All stats are decreased by 50 to remain within -100 and +100.
0 is the origin point.
When you roll a 100, you add your SL there directly. If your Agility is -70, you add -7 to the roll. If your thoughness is +10, you add +1 to the result. The result is a 10 SL range roll represented by a d100+the attribute bonus. Min dice is 0, dice is 10 SL

At the wildest of cases, rolls can be: -10SL or +20SL

If I have -5 AGL, and 2 Ballistic skill, and I roll the d100 for a test, lets say i get a 5SL result from the dice. My skill + attribute adds -3 to result in a 2SL final result.

Make the d100 a d10 i instead and count critical hits by if it rolls a 1 or a 10. This, in theory doesnt change the possiblity of criticals??? Yes.... It really does not. Alright before it was truly 10% for crits, now it holds 20% of the space but for a fail or a success, it was always 10% before and it still is, seperately. Now 20% of all rolls are crit, its a good change really idc

> [!claude] Claude · 2026-10-31
> **Eskiden gelenler için genel çeviri kuralları** ([[Uyarlama Soru Listesi]] U01–U05). Eski notlara dokunulmaz, kural burada bir kere yazılır; [[Actions]] ve diğer notlardaki çevrilmiş sayılar bunu kullanıyor.
>
> | Konu | Kural | Soru |
> |---|---|---|
> | d100 modifier'ları | Eski ±10 = ±1 (SL ya da stat). ±5 yuvarlanır. Ör. Flanking +20 → +2SL, Pace aşımı -30 → -3SL, Gürültü -20 → -2SL. | U01 |
> | Rastgele tablolar | Test zarı değiller, **d100'de kalır**: [[Roll Tables]], Random Race / Realm / Continent / Keywords ([[Karakter Açılışı]]). Events Table zaten d10 + KARMA, olduğu gibi kalır ([[Tokens]]). | U01 |
> | Kritik | Doğal **10** kritik başarı (SL ×2), doğal **1** kritik başarısızlık. Eski "doubles" (22, 66, 100) kalktı. | U02 |
> | Kritik alanını genişletenler | Point of Success: **9** da kritik. Gamblers Favour: **2 ve 9** da kritik, "mad" hali **3 ve 8** de. Talih Puanı doğal 10'da kazanılır, doğal 1'de kaybedilir. Dream Weaving felaketi doğal 1. | U02 |
> | SL ölçeği | Eski SL sayıları aynen girer: silah hasarları (`2SL+5`), Dream Weaving 1–11SL, keyword eşikleri (Momentum 6SL+, Butcher 10SL+, Skeletal Posession 4SL+), Targeted Hit -1…-3SL, Stances ±2SL. | U03 |
> | Hasar ve etki zarları | Sadece test zarı d10. d6+2, d10+5, ExtraEssence\*d6+8, d4 iyileştirme, d6 Turnout tablosu aynen. | U04 |
> | Bonus (B) | Eski SB, TB, AGB, THB, WPB, STB… yerine yeni bonus (stat'ın -10'a uzaklığı), **birebir**. | U05 |
>
> - 🚩 ±5 hangi yöne yuvarlanıyor? Önüne çıkanlar: Luminary uzuvları (+5 STR…), Events Table (-5 / +5 END), Arik'Xea AGI `3d10+20` (ortalama +5,5), Cam Erikan `3d10+10` (ortalama -4,5). Öneri: en yakına, tam 5 yukarı (±5 → ±1). Ama o zaman Luminary'de +5 ile +10 aynı şeye dönüyor, bkz. [[Style Notes#Classlar]].
> - 🚩 Yukarıdaki not: kritik artık zarların %20'si. Kritikte Turnout ([[Tokens]]) da tetiklendiği için Turnout eskisinden iki kat sık çıkacak.

## Attributes:

The origin starts from -5 and increases over time with milestones up to 0.

An INT based character stat example at the origin point of -5

Distance from the origin
  -1      +1      -3     -1     +3    +1
| STR | AGL | THG | CHR | INT | WP |
|  -6   |  -4   |   -8  |  -6   |  -2  |  -4  |
Pure stats

Bonus Stat: Stat distance from -10 , so the bonuses of this example stats above is: 4, 6, 2, 4, 8, 6
Passive Stats: -2 of bonuses with an added negative sign:
-2, -4, 0, -2, -6, -4  (directly add to the enemy dice)

HEALTH: THGBx2
ENDURANCE: STRB+WPB
RES: Base+Armor
PACE: 3 + (1 for every 4 AGB) (accordingly with time shard system)
MOV: AGLB
ESNC: Foc+WPB+Race

> [!claude] Claude · 2026-10-31
> **Türetilmiş statlar: eskiden gelen kararlar.** Üstteki satırlara dokunulmadı; değişmesi gerekenler 🚩.
>
> | Stat | Yukarıda | Karar | Soru |
> |---|---|---|---|
> | PACE | `3 + (1 for every 4 AGB)` | 🚩 **10**, eski evrensel taban. Irk notunda farklı Pace varsa o. Time shard'lar kalkıyor, bkz. [[#Pace]]. | U10 |
> | MOV | `AGLB` | 🚩 **AGLB × 2** (eski formül, yeni bonusla). Hareket kuralları: [[Actions]]. | U14 |
> | ESNC | `Foc+WPB+Race` | Geçerli. 🚩 [[Soul Surge]]'teki HOT TAKE (Focus'u esans artışından ayır, sadece WP arttırsın, yoksa ucuza "OMEGA MAGE" çıkıyor) **ciddi değerlendirilecek**. | U24 |
> | HEALTH, END, RES | yukarıdaki | Karar yok, yeni formüller geçerli. Eski [[Attributes ve Skills]] sadece referans: HP `SB + TBx2 + WB`, END "Health'le aynı", RES zırh + doğal deri. | — |
>
> - **Irk formülü evrenseli ezer (U09).** Bir ırkın kendi HP / END / RES / MOV / ESNC / PACE formülü varsa o ırk için o geçer. Formüldeki S / T / W / AB yeni bonuslarla okunur (U05). Oren `WP+FOR+2` ve Vikos `WP+CH` ESNC'leri ırka özel kalır. Irk ırk tablo: [[Style Notes#Erikanlar]].
> - **Irk attribute modifier'ı (U08).** Irk, başlangıç dağılımının üstüne +1 / -1 ekler (eski zar farkı ±10 → ±1). Tablo yine [[Style Notes#Erikanlar]]'da.
> - **Essence kuralları** (eski [[Soul Surge]], bütün beceri sistemleri için ortak): uzun dinlenme tam doldurur, kısa dinlenme yarısını; yemek ve uyku önemli. ESNC sıfırlanınca bayılırsın. Bir şekilde eksiye düşersen her negatif esans için d10+2 draining hasar. Kara Yürek'in **Öz**'ü aynı havuz (U23).
>
> **Passive Status Checks** (eski [[Attributes ve Skills]]): yukarıdaki "Passive Stats" ile aynı fikir, aynı -2'lik hesap. Boşta dururken biri senin pasifine karşı bir şey yaparsa pasifin onun zarına zorluk olarak eklenir.
>
> | Pasif | Neye karşı | Örnek |
> |---|---|---|
> | STR | hazırlık, aksiyona hazır sertlik | seni itmeye çalışan pasif STR'ını geçmeli |
> | AGL | refleks | sana bakarken gafil avlamaya çalışan pasif AGL'ını geçmeli |
> | THG | beden bütünlüğü, sağlamlık | sersemken kemiğini kırmaya çalışanın STR zarına pasif THG'ın girer |
> | INT | algı, olayların ve çevrenin zihinsel takibi | yanından sızmaya çalışanın zarına |
> | CHR | sosyal farkındalık, soğukkanlılık, sezgi | yalanla seni etkilemeye çalışan pasif CHR'ını geçmeli |
> | WP | ruhsal soğukkanlılık, irade, vizyon | seni iradesine almaya çalışan büyü pasif WP'ni geçmeli |
>
> - 🚩 Bonusu 2'nin altındaki statlarda pasif pozitife dönüyor (bonus 1 → +1, yani düşmana kolaylık). Bilerek mi?

## Skills:
You can have 2 skills max at the same level. For every Skill you increase, you decrease another one. If you're being tested on a negative scored test, you get the disadvantage.

> [!claude] Claude · 2026-10-31
> **Eskiden gelen skill kuralları** (U15, U16)
> - Limit aynen yukarıdaki gibi: aynı seviyede en fazla 2 skill, sıfır toplam, -5…+5. Eski "seviye başına 4 slot" ve 1–5 seviyeler kalktı.
> - **Ek kural (U16):** bir skill'i bir üst seviyeye çıkarmak için o anki seviyesinde **en az 1 başka skill** olmalı.
> - Bu kurala dokunan iki keyword yeniden yazıldı: **Jack of All Traits** (her alınışta herhangi bir negatif skill'e +1) ve **Sun Blind** (skill'e değil attribute'a etki eder). Tam hali [[Feats#Keywords]] altındaki keyword tablolarında.
> - 🚩 Aşağıdaki "maxed out" örneğinde eski kısaltmalar duruyor: BL → Accuracy, WP (Weapon Skill) → Combat, INV → Awareness. Craft listede yok (19 eski skill, yeni listede 20). Yeni listeyle güncellemek isteyebilirsin.

Example of a maxed out characters skillpoints spread uniformly:
- ACB:    +5
- ANC:   +5
- ATL:    +4
- SWF:   +4
- BL:      +3
- WP:     +3
- EXPR:  +2
- DEC:   +2
- HEAL:  +1
- INST:     0
- MNT:   -1
- STH:    -2
- SOH:    -2
- FORT:   -3
- SCHO: -3
- SUR:    -4
- COG:   -4
- INV:     -5
- FOC:    -5


### New Skills:
PHYSICAL
- Acrobatics : Elaborate delicate movements mastered with technique
- Athletics : Raw power, wrestle, relying on the magnitude of strength
- Swiftness : Quick movement with pace, relying on speed and rapid movement
- Fortitude : Embracing to the bone, rely on mass and sturdiness of your body

ACTION BASED:
- Accuracy : Ballistic Skill, precision, efficiency, mental accuracy too, guessing or sensing the correctness
- Combat : Close dynamic interactions, impactful hits, obvious and intimate actions
- Stealth : Out of sight movement and hidden actions, reading others for unforseen actions
- Slight of Hand : Elaborate technical moves, rapid hand movements, finesse, pickpocketing, disarming etc.
- Mount : Used in riding animals or herding them really, but in truth, can be used in motion based on another creature

SOCIAL
- Expression : Agreeableness and truth (embrace and convince)
- Deception : Divert and lie (divert and missuse)

MENTAL
- Awareness : Investigation, overall perception, reading of the room and social clues
- Instincts : Intuition, gut feeling, a very general feeling of non specifity that isnt rational but always accurate (a dangerous situation should always be a huge redflag, tho if the palyer used cognition or awareness maybe they would realize its not really dangerous cause of reasons, no such evaluation on instinct, it just screams positive or negative)
- Focus : Channelling the soul, mind and/or body

EVALUATIVE
- Survival : Things tied to direct environmental survivorship knowledge against the world or its inhabitants
- Scholar : Wisdom, knowledge, rooting an idea in facts and finding explonations based on characters expertiese
- Cognition : Intelligent elaboration, design, plan and connecting the dots
- Craft: Manipulate objects to make new things.
- Animal Care: Asses, approach and handle animals.
- Healing: Asses, identify and treat illness/wounds.

> [!claude] Claude · 2026-10-31
> **Skill stat çiftleri** (U15): eski [[Attributes ve Skills]] tablosundaki çiftler **varsayılan**, GM duruma göre değiştirebilir. Yeni skill'ler selefinin çiftini alır.
>
> | Skill | Grup | Varsayılan çift | Selef |
> |---|---|---|---|
> | Acrobatics | PHYSICAL | AGL / STR | aynı |
> | Athletics | PHYSICAL | STR / AGL | aynı |
> | Swiftness | PHYSICAL | AGL / STR | aynı |
> | Fortitude | PHYSICAL | THG / WP | aynı |
> | Accuracy | ACTION BASED | AGL / STR | Balistic Skill |
> | Combat | ACTION BASED | STR / AGL | Weapon Skill |
> | Stealth | ACTION BASED | AGL / CHR | aynı |
> | Slight of Hand | ACTION BASED | AGL / INT | aynı |
> | Mount | ACTION BASED | AGL / STR | aynı |
> | Expression | SOCIAL | CHR / INT | aynı |
> | Deception | SOCIAL | CHR / AGL | aynı |
> | Awareness | MENTAL | INT / CHR | Investigation |
> | Instincts | MENTAL | WP / THG | aynı |
> | Focus | MENTAL | WP / THG | aynı |
> | Survival | EVALUATIVE | INT / THG | aynı |
> | Scholar | EVALUATIVE | INT / CHR | aynı |
> | Cognition | EVALUATIVE | INT / CHR | aynı |
> | Craft | EVALUATIVE | 🚩 **açık** | yok |
> | Animal Care | EVALUATIVE | CHR / INT | aynı |
> | Healing | EVALUATIVE | INT / WP | aynı |
>
> - 🚩 Craft'ın çifti lazım. Adaylar: AGL / INT (Slight of Hand'e yakın el işi) ya da INT / AGL (tasarım ağırlıklı, Cognition'a yakın).
> - 🚩 Eski Night Secrecy keyword'ü "birden çok disiplin için birden çok Scholar skill'i" istiyordu. Yeni listede tek Scholar var; disiplin başına ayrı Scholar mı olacak?

# Pace

> [!claude] Claude · 2026-10-31
> 🚩 **Bu bölümün kaderi (U10, U11, U12):** time shard yok, eski turlar geri geliyor. Aşağıdaki shard tasarımı (3 shard, Rogue Pace, contested / uncontested ruling'ler, "kaybeden otomatik başarısız", "uzun menzil kazanır") **LEGACY SYSTEM'e taşınacak**. Taşımayı Obsidian içinden sen yap, linkler kırılmasın. Shard'a bağlı olmayan fikirler ("Take to the heart", "Actions effect each other… loser -1 Pace", kılıç savuruşunu yarıda bloğa çevirmek) kalsın mı, sen bak.
>
> **Yeni sistemde Pace (eski [[Combat Rulings]] haliyle)**
> - Herkesin tabanı **10 Pace**. Irk notunda farklıysa o ([[Style Notes#Erikanlar]]).
> - Aksiyon alırken Pace harcarsın. Son aksiyonun Pace limitini aşarsa, aşılan her Pace için o aksiyona **-3SL** (eski -30).
> - Silah saldırıları silahın Pace'i kadar: P(x), doldurma R(x) ([[Actions]]).
> - **Half action 2 Pace**, ardışık her half action'a +1 Pace.
> - Bütün Pace'ini harcayarak bir kez daha koşabilirsin (ikinci Move Action).
> - Basit bedensel hareketler 1 Pace olabilir. GM başka aksiyonlara Pace biçebilir.
> - **Pace Borrowing:** bir aksiyonu sonraki tura uzatabilirsin. 2 Pace'in kaldı, silahı doldurmak 4 Pace: "dolduruyorum" dersin, sonraki tur 2 Pace daha harcayıp bitirirsin. Arada bölünmemen lazım.
> - Eski bütün Pace bedelleri olduğu gibi geçer: silah P / R, +2 Pace keywordleri (Furious Assault, Heavy Weaponry, Core Arsenal, Swift in Arms, Ambidextrous, Retaliate, Brief Composure, Battle Frenzy, Masochist, War Heart Rampant), Stagger -2 Pace, Attributes Evolved 8, Dive 3, Outpacing Predator 7, Instrument Aide 2, Marrow Walker "düşmanın HP'si kadar", Kharan'ın asılı kalırken +1'i.
> - 🚩 **Dual Wielding** üç yerde üç türlü: [[Combat Rulings]] "+2 Pace on using that item" (bedel mi?), [[Combat Specials]] "ekstra aksiyonlara +10" (→ +1SL), Ambidextrous "dual wielding'de +2 Pace" (kazanç). Hangisi ya da hangileri birlikte?
>
> Savaşın geri kalanı (initiative, turlar, half action'lar, hareket): [[Actions]].

All combat is divided into 3 time shards. Player Pace fits into the shards equally. Each shard runs like a beat of the battle, a simultenous, back and forth, effecting the next shards with its outcomes. The system is soft, and the narrative of the event is always the priority. The Pace division is a tool for easier tracking. Rules below may help but may not always enforced.

Take to the heart:
Simply put, Pace tracks how long something takes and how many things a skilled person can do within a fixed time. If you act with less pace costs, you get to react. If you act with high costs, you get reacted on all the time.

Rules:
- Two actions concluding at the same points are contested, and if both succeed, the longer range one wins, if the same range, the higher SL wins. Winning also causes the other side to automatically fail.
- Actions only get cancelled/interacted with at the end of shards. So if I do two sword attacks in the shard using 4 Pace, although the enemy uses a stunning strike and a grapple, they contest only with the second one of my attacks. So within the shards, there is an un-interuptable safe zone that you can do whatever you want without contest. (this is the MOST ignorable rule. If 2 action aligns with 2 other actions, simply allow intervention.)  
- Actions that end earlier within the time shard, executes without contest.
- Two person contesting only meaningfully effect each others next actions on shard conclusions. Even though the opponent is charging an attack, and you're punching their face ever Pace, if it concludes within the shard, it doesn't get effected. So more Pace means less leakage and more to work with without interruptions. But for the next shard, all the punches take your pace.
- ~~Two person contesting within the same shard, one has 3 Pace and one has 2 Pace, since the 3 pace person divides the shard into smaller fractions, having more of a chance to block or response. So it looks like this: 1x.1x.1x interacts with 1y.1y and time follows like this: 1x,1y,1x,1y,1x. An another ruling for this is the matching up to last logic. The quicker one matches with the upcoming fraction of the 2 Pace one, so: 1x-1y, 1x-1y, then 1x OR 1x-1y, 2x-1y, OR 3x-2y, So the 2 pace matches with whatever next on the 3 pace guys actions.~~
- Actions effect each other. Misdirect, stop, reflect or cause various effects. Those often make the loser have -1 Pace on the next shard.
- Combattants can postpone or cancel an action to do other actions that don't conflict. Like turning a sword swing into a block halfway, losing the damage but defending yourself. Postponing the sword attack for 1 Pace and dashing ahead.
- When the two combattants with different paces clash, the higher Pace owner is reduced to the lower ones, and their extra Pace becomes rogue Pace. For example: a 6 Pace and a 10 Pace entity clashes. The 10 Pace gets reduced to 6 and time shards are divided as 2|2|2. Then they have 4 Rogue Pace that they can utilize freely.
- Rogue Pace is a unit of Pace hovering without being stuck on a shard and when used, an action loses 1 Pace cost.(use the basic alternative, this is advanced in general). If I have 2 hovering Rogue Pace and 2 Pace per shard, I can use both of the rogue paces to lower the cost by -2, and instantly use a 4 Pace action within a 2 Pace time shard.
EXAMPLE:
Pace 6:
2|2|2
Pace 7:
2|2|2 and 1 rogue
Pace 8:
2|2|2 and 2 rogue
Pace 9:
3|3|3

Alt ruling without the rogue pace do this:
Pace 6:
2|2|2
Pace 7:
3|2|2
Pace 8:
3|3|2
Pace 9:
3|3|3


## An example fight with 3 rulings:
Bir shard deklerasyon zaman dilimi, 3-4 saniyelik bir zamanı temsil ediyo reelde. O zamanda geçen aksiyonlar GM ve oyuncuyunun anlatısına göre eşleşip contestliyolar. Kural da ne kadar aksiyon sıkıştırırıp aşağı yukarı ney ne noktada neyi bölüyo denkleşiyo onu hesaplıyo hepsi bu. Aşağıdaysa aynı savaş karşılaşması üç kural sistemiyle ele alınıyor, biri shard içi hamlelerin birbirini bölebilmesini, diğeri bölememesini, sonuncusuysa time shard olmayan sade sistemi ele alıyor.

Senaryo şu: Şövalye ve süikastçi karşılaşır. Gerilim büyük, iki tarafta 12 PACE'E sahip ve bu Shardlara 4 4 4 ayrılmış. Birbirlerini gözlüyorlar ve aksiyon başlıyo:

GM ŞUNA GÖRE RULING SEÇEBİLİR:
With contested time shards: Maximum rekabet ve etkileşim ancak çok yavaş ve temposu düşük, özellikle yüksek Pace seviyelerinde.
With uncontested time shards: Yüksek rekabet ve etkileşim. İdeal.
Without time shards: Düşük rekabet ve etkileşim, harika tempo, gel, saldır, tepki ver, bitir. Karmaşık sahneler ve kalabalık oyuncu grupları için ideal.
### Ruling With Contested Shards:
Shard içindeki olaylar aynı zaman dilimlerine denk geldikçe çarpışır.

Şövalye 2 Pace üzeirnden 2 kere kılıç sallıyo = 4. Shardın 2. ve 4. Pacelerinde saldırılar yaşanacak. Süikastçi 1 consantre, 1 dodge, 1 dash ve 1 stab atıyo. 1. 2. 3. 4. Pacelerden 2 ve 4'te contest var. Consantrasyon uncontested, dashle kılıç saldırısı contestliyor ve diyelimki süikastçi kazandı, devam. Sonra dash uncontested ve stab geliyo bam stab kılıca contesti kaybediyor, kılıç iniyo göğsüne. Şimdi sıradaki shardda kanar halde ve yalpalamış giriyor süikastçi. Eğer stabi başarsa, kılıççı onu uzaklaştırmakla uğraşmalı ya da kılıçtan başka bir alternatif değerlendirmeliydi.

(Eğer 2 paceleri olsaydı zaten direk shard sonuna denk gelecekti bir saldırı, rakipse aynı şekilde birer aksion alarak ortada da bölebilirdi sonda da contestleyebilirdi. Eğer 3 Pace olsa 1 liğin erken 2 liğin sonra yaşanır veya tam tersi, senin aksiyon dizmene göre. Kalanı da tamamen GM imagination ına bağlı.)
### Ruling With Uncontested Shards:
Zaman dilimi neticelenene dek hiçbir aksiyon bölünemez.

Şövalye 2,2 = 4 Pace ile 2 kere kılıç savurdu. Süikastçi ilk saldırıyla zaten contestleyemediği için mecburen etkileşimsiz aksiyonlar seçiyor. Dash 1, stab 1, stab 1, dodge 1 atıyor. Yaşanan olayda yalnızca ikinci kılıç saldırısı ve dodge contestliyor, diğer her şey tarfların zarı geçtiği an uygulanmış oluyor. Düşük dinamizm ancak net sonuçlar. Bu sistem özellikle düşük Pace seviyelerinde idealdir.

### Ruling Without Time Shards:
Temel sistem uygulanır. Turlar eşlenik zaman alanında değil, initiative sırasına uyarak tek seferde olur biter. Karşı taraf half action kullanarak istediği saldırıya reaksiyon gösterebilir. Eğer birden çok rakiple oyuncu savaş halindeyse bu sistem önerilir.

Süikastçi önceliklidir ve 12 Pace'inin 10 unu bıçak darbesi atıp 2 sini tepkilere saklar. Şövalye 2 Pace'i tepkiye harcayarak bıçakların hasarını zırhına soğurtur, ardından kalan 10 Pace'i ile 5 kere kılıç savurur. Süikastçide bunların 2 sinden sıyrılmaya çalışır.

> [!claude] Claude · 2026-10-31
> U11: shard'lar LEGACY'ye gidince yukarıdaki üç ruling'den sadece **Ruling Without Time Shards** kalıyor. Metni = eski Steps of Combat + Initiative, yazılı hali [[Actions]]'ta. Örnekteki 12 Pace eski ölçekle (taban 10, ırka göre değişir) uyumlu.
