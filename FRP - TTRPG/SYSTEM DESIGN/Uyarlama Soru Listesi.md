---
yazar: claude
tür: oyun-tasarımı
proje: "[[NERRATIVE SYSTEM]]"
durum: aktif
tags:
  - ttrpg
  - sistem-tasarımı
---

> [!claude] Claude · 2026-10-29
> # Uyarlama Soru Listesi
> Eski rulebook (arşiv) yeni sisteme ne kadar ve nasıl giriyor? Eski sayfaların kendi içindeki tutarlılığı artık konu değil, burada sadece **eski ↔ yeni** çelişkileri var.
>
> **Üç kural**
> 1. Eskiden gelip yeni sistemle çelişmeyen her şey kabul. Liste: [[Yeni Sistem İnşa Panosu]].
> 2. Çelişkiler burada soruluyor: nasıl uyarlanacak.
> 3. Arşivden hiçbir şey silinmiyor. Eski notlar ([[Kurallar/Combat Rulings|Kurallar]], [[Soul Surge|Beceri Sistemleri]], [[Roll Tables|Tablolar]], [[Arik'Xea|Erikanlar]]) olduğu gibi kalıyor. Yeni sistem notlarına ([[NERRATIVE SYSTEM]], [[Style Notes]]) dokunulmuyor, cevaplara göre sen yazıyorsun.
>
> **Yeni sistem** = [[NERRATIVE SYSTEM]] + [[Style Notes]]. **Eski** = rulebook'tan aktarılan notlar.
> Durum: ⬜ cevap bekliyor · 💬 cevaplandı · ⭐ başka soruları kilitleyen temel soru (önce bunlar).
> Cevabı `- Cevap:` satırına yazman yeterli; harf de olur ("b, ama…").

> [!claude] Claude · 2026-10-29
> ## 0. Usul
> **U00** ⬜ **Eski sayfalar kendi arasında farklı değer verdiğinde hangisi yeni sisteme girer?** (ör. Kharan ESNC: Opening tablosu `-1`, ırk notu `WP+Foc+1`; Vikos PACE 4 ↔ 10)
> - (a) Özel sayfa genel tablodan üstün (ırk notu > Opening tablosu, beceri sayfası > Keywords özeti)
> - (b) Daha yeni tarihli sayfa kazanır
> - (c) İkisi de panoya seçenek olarak yazılır, sen seçersin
> - Cevap:

> [!claude] Claude · 2026-10-29
> ## 1. Zar ve sayısal ölçek
> **U01** ⭐ ⬜ **d100 sayılarının çevirisi.** Eski kurallarda ±10'luk modifier'lar her yerde: Flanking +20/+40, Pace aşımı -30, Wounds +20/+50/-10, Grapple +20, Dual Wielding +10, Çoklu Hamle +10/+20, menzil dışı -30, Gürültü -20, Fencer +10, Soft Tissue -10, Night Owl +10, Biçim Değişimi +10, Attributes Evolved 10, Severe Deformation ±20, Events Table ±10 stat, Luminary uzuvları +5/+10 STR. Yeni: SL doğrudan, attribute'lar -10…+10 ([[NERRATIVE SYSTEM#Stats]]).
> - (a) Tek genel kural: her ±10 = ±1 (SL ya da stat), ±5 = yarım → yukarı/aşağı yuvarla. Notlara dokunulmaz, kural bir kere yazılır.
> - (b) Genel kural + bazıları için istisna (hangileri?)
> - (c) Her biri tek tek
> - Ek: Roll Tables, Random Race/Realm, Random Keywords gibi **rastgele tablolar** d100'de kalabilir mi (test zarı değiller)?
> - Cevap:
>
> **U02** ⬜ **Kritikler: doubles → 1 ve 10.** Eski: 22, 66, 100 gibi çiftler kritik. Yeni: d10'da 1 ve 10. Buna yaslanan eski şeyler:
> - Point of Success ("1-10 da kritik"), Gamblers Favour ("1-10 ve 91-100", "1-20 ve 81-100"): d10'da kritik alanını nasıl genişletir? (a) 1-2 / 9-10 olur (b) kritikte ekstra etki verir (c) başka
> - Talih Puanı "10 ve üzeri / 90 aşağısı": doğal 10 / doğal 1 mi?
> - Dream Weaving "If over 90… Youre fucked": doğal 1 mi, belli bir -SL mi?
> - Random Hit Locations "d100'ü ters çevir": ayrı d10 mu, kaldırılsın mı (zaten "ignore unless necessary" diyor)?
> - Cevap:
>
> **U03** ⭐ ⬜ **SL ölçeği aynı mı sayılsın?** Eski SL = stat'ı geçtiğin her 10 (pratikte ~-6…+6). Yeni SL = d10 + attribute + skill (-10…+20). Eski SL'ye bağlı her şey: silah hasarları (Uzun Kılıç `2SL+5`), Dream Weaving 1–11SL, keyword eşikleri (Momentum 6SL+, Butcher 10SL+, Skeletal Posession 4SL+), Targeted Hit Location -1…-3SL, Stances ±2SL.
> - (a) Aynı ölçek, eski SL sayıları olduğu gibi girer
> - (b) Yeni SL daha geniş, eşikler/çarpanlar ölçeklenir (nasıl?)
> - Cevap:
>
> **U04** ⬜ **Hasar ve etki zarları** (d6+2, d10+5, ExtraEssence\*d6+8, d4 iyileştirme, d6 Devam Simgeleri tablosu…). d10'a geçiş sadece test zarı için mi?
> - (a) Sadece test zarı d10, hasar/etki zarları kalır
> - (b) Hepsi d10 ailesine çevrilir
> - Cevap:
>
> **U05** ⬜ **"B" (bonus) değerlerinin ölçeği.** Eski bonus = stat'ın onlar basamağı (~2–6). Yeni bonus = stat'ın -10'a uzaklığı (başlangıçta ~3–7, sonda ~5–15). Bonusla çalışan eski formüller: Claws/Muşta `SB`, zırh Cüsse `C:4–6` (SB/TB şartı), Jumping `STR/2 m`, düşüş `AGB/THB m`, Unyielding `THB-5`, Hard Bones `+TB`, Agonist `+WPB`, Shove, Dashing Strike `STB`.
> - (a) Yeni bonus birebir yerine geçer
> - (b) Yeni bonus yarıya bölünerek kullanılır (ya da başka çarpan)
> - (c) Tek tek
> - Cevap:

> [!claude] Claude · 2026-10-29
> ## 2. İlerleme
> **U06** ⭐ ⬜ **XP → milestone.** Yeni sistemde XP yok, 44 milestone var ([[NERRATIVE SYSTEM#Progress]]). Eski XP fiyatlı her şey:
> - Skill/attribute XP tabloları, keyword her 1000 XP ([[General Rulings]])
> - Başlangıç XP'si, Random Opening ödülleri (+500 XP, random keyword başına +100 XP) ([[Karakter Açılışı]])
> - Instrument Aide yetenekleri (100 XP + artan), Extra Abilities (200 XP…)
> - Luminary Core Strength (1500–3000 XP), Fuzed Metal "NEEDS MUCH MORE XP"
> - Keywordler: Night Owl ("XP harcarken +10"), Sun Blind ("XP bedelleri yarı"), The Know-All Person (+4 keyword slot), Lifelong Variety (+2 keyword)
> - Seçenekler: (a) her XP bedeli milestone hakkına çevrilir (ör. 1 Instrument Aide yeteneği = 1 "+Keyword" adımı) (b) beceri sistemleri için ayrı bir "beceri puanı" milestone'a eklenir (c) XP ikinci para birimi olarak yaşar (d) tek tek
> - Cevap:
>
> **U07** ⬜ **Tier'lar: 7 → 5.** Eski 7 tier (ORDINARY FOLK → A GOD AMONG MEN, XP, keyword sayısı, Wealth, açıklama). Yeni 5 tier, 8–9 milestone. Eski tier açıklamaları ve Wealth tablosu yeni tier'lara nasıl girsin?
> - (a) 7 açıklama 5'e indirilir: hangileri birleşir/düşer? (6 ve 7'nin metni zaten aynı)
> - (b) Açıklamalar "anlatı seviyesi" olarak ayrı kalır, mekanik tier'dan bağımsız
> - (c) Wealth tablosu yeni tier başına kalır / kaldırılır
> - Cevap:

> [!claude] Claude · 2026-10-29
> ## 3. Karakter açılışı ve statlar
> **U08** ⭐ ⬜ **Irkların attribute farkı.** Eski: zarla atılıyor, ırka göre zar değişiyor (Kharan AGI `2d10+30`, THG `2d10+10`; Cam Erikan hepsi `3d10+10`…). Yeni: hepsi -5 origin'de, sabit dağılım (+2, +1, +1, -1, -1, -2) ([[NERRATIVE SYSTEM#Progress]]).
> - (a) Irk, dağılımın üstüne modifier ekler (+10 → +1, -10 → -1)
> - (b) Irk attribute'a dokunmaz, sadece keyword ve türetilmiş statla ayrışır
> - (c) Irka özel dağılım şablonu (ör. Kharan'da +2 AGL'ye kilitli)
> - Ek: Random Opening'deki "attribute'ları rastgele at" seçeneği yeni dağılımda yaşıyor mu (ör. 6 değeri zarla yerleştir)?
> - Cevap:
>
> **U09** ⬜ **Türetilmiş statlar: evrensel formül mü, ırk formülü mü?** Yeni: HEALTH `THGBx2`, END `STRB+WPB`, MOV `AGLB`, PACE `3 + her 4 AGB için 1` ([[NERRATIVE SYSTEM#Attributes]]). Eski ırk sayfaları kendi formülünü veriyor: Oren HP `S+3T+W`, MOV `2AB`; Cam Erikan / Azothan END `no` / `Puppet HP`; Vikos END `3HP`; Dweller PACE 12, Vikos PACE 4…
> - (a) Evrensel formül + ırk modifier'ı (ör. Oren HP +X, MOV x2)
> - (b) Sadece özel durumlar kalır (END yok, Puppet HP, MOV x2), sayısal farklar düşer
> - (c) Irk formülü evrenseli ezer
> - Ek: ESNC zaten uyumlu (`Foc+WPB+Race`, ırk notları `WP+Foc+N`). Ama Oren `WP+FOR+2` (Fortitude), Vikos `WP+CH` (Charisma) diyor: bu ırklara özel kalsın mı?
> - Cevap:

> [!claude] Claude · 2026-10-29
> ## 4. Pace ve savaş akışı
> **U10** ⭐ ⬜ **Pace ölçeği.** Eski: herkes 10 Pace (ırka göre 4–12). Yeni: `3 + her 4 AGB için 1`, yani karakterler kabaca 4–6 (örnek dövüşte 12 kullanılmış). Eski bedeller bu havuza göre büyük:
> - Silahlar P(2)–P(11) (Koca Kılıç 11, Cellat Baltası 9, KNDS 10), reload R(1)–R(20)
> - Half action 2 Pace (+1 ardışık), Instrument Aide her beceri 2 Pace, Attributes Evolved 8 Pace, Dive 3 Pace, Marrow Walker "düşman HP'si kadar Pace", Outpacing Predator 7 Pace
> - Keyword kazançları: +2 Pace (Furious Assault, Heavy Weaponry, Core Arsenal, Swift in Arms, Ambidextrous, Retaliate, Brief Composure, Battle Frenzy, Masochist, War Heart Rampant), Stagger -2 Pace, Kharan uçuşta +1 Pace ([[Style Notes]])
> - Seçenekler: (a) eski bedeller sabit bir oranla küçülür (ör. yarıya, yukarı yuvarla) (b) yeni Pace formülü eski bedellere göre büyütülür (c) bedeller kalır, sadece keyword kazançları küçülür (+2 → +1) (d) tek tek
> - Cevap:
>
> **U11** ⭐ ⬜ **"Tur" diyen eski kurallar time shard'larda ne demek?** Eski [[Combat Rulings]]'in "Steps of Combat"ı (initiative, sıra, tur sonu) yeni sistemdeki **Ruling Without Time Shards**'ın ("temel sistem, initiative sırası") metni olarak kabul edilebilir. Ama shard'lı iki ruling'de "tur" geçen kurallar: Bleeding/Burning "her tur", Stagger "-2 her tur", Concentration "sonraki tur +3SL", Pace Borrowing "sonraki tura uzat", Momentum "per turn", Move Action "turda bir bedava", Crawling "her tur 1 Revivify", Ready Action, Forseen Paths "initiative'de iki kez".
> - (a) Tur = 3 shard'ın tamamı
> - (b) Tur = bir shard
> - (c) Kurala göre değişir (hangileri?)
> - Ek: Steps of Combat'ı time shard'sız ruling'in metni olarak kabul ediyor musun?
> - Cevap:
>
> **U12** ⬜ **Opposing Tests: ikisi de başarırsa.** Eski: "ikisi de başarırsa ikisi de istediğini yapar, yüksek SL'li yine de işini görür". Yeni: aynı noktada biten iki aksiyonda önce menzil, sonra yüksek SL kazanır ve **kaybeden otomatik başarısız** olur ([[NERRATIVE SYSTEM#Pace]]).
> - (a) Yeni kural her yerde geçerli, eski olan arşivde
> - (b) Yeni kural sadece shard'lı ruling'lerde, eski kural shard'sız ruling'de
> - Cevap:
>
> **U13** ⬜ **Half Actions.** Eski: "2 half action = 1 full action", "bir anda 1 aksiyon", half action 2 Pace. Yeni: her şey Pace, half action shard'sız ruling'de tepki olarak geçiyor. Eski Half Actions listesi (Block, Soak, Dodge, Dash, Shove, Aim, Lock In, Counter…) ne olsun?
> - (a) "Kısa hamleler" menüsü olarak kalır, bedelleri Pace'e çevrilir (U10'a bağlı)
> - (b) Tepki menüsü olur (sadece reaksiyon)
> - (c) "Half action" kavramı kalkar, liste sadece aksiyon örnekleri
> - Cevap:
>
> **U14** ⬜ **Hareket.** Eski: MOV metre (`AB*2`), turda bir bedava Move Action, ikincisi "tüm Pace"; uçma x2, sürünme /4, tırmanma /8; Dash `Mov/2`. Yeni: MOV `AGLB`, hareketin Pace bedeli tanımlı değil.
> - (a) Çarpanlar ve Dash kalır, "tüm Pace" kuralı shard'a uyarlanır (nasıl?)
> - (b) Hareket de Pace'le ödenir (metre başına / MOV başına X Pace)
> - Cevap:

> [!claude] Claude · 2026-10-29
> ## 5. Skill'ler
> **U15** ⬜ **Eski 19 skill → yeni liste eşlemesi.** Önerilen eşleme (onayla/düzelt):
>
> | Eski | Yeni |
> |---|---|
> | Weapon Skill | Combat |
> | Balistic Skill | Accuracy |
> | Investigation | Awareness |
> | Animal Care, Mount | Pure Skills |
> | Healing | **?** (yeni listede yok) |
> | Acrobatics, Athletics, Swiftness, Fortitude, Stealth, Slight of Hand, Expression, Deception, Instincts, Survival, Scholar, Cognition, Focus | aynı ad |
>
> - Healing için: (a) Scholar'a girer (b) Craft'a girer (c) Surgeon/Herbalist keyword'üne bağlanır (d) yeni skill olarak geri gelir
> - Eski tablodaki **bağlı stat çiftleri** (Acrobatics AGL/STR…) yeni skill'lerin varsayılan çifti olsun mu? Yeni gelenler (Accuracy, Combat, Awareness, Craft) eski karşılığının çiftini mi alsın?
> - Cevap:
>
> **U16** ⬜ **Skill limiti 4 → 2 ve skill seviyeleri.** Eski: aynı seviyede 4 skill, seviyeler 1–5 (XP tablosu "to 5"). Yeni: aynı seviyede en fazla 2, sıfır toplamlı (biri artarsa biri düşer), -5…+5. Buna bağlı eski keywordler:
> - Jack of All Traits (limit +2 → 4 mü olur, +1 mi?)
> - Sun Blind (cezası "sadece 2 slot", yeni sistemde zaten 2: ceza 1 slot mu olur, başka bir şey mi?)
> - Eski "seviye 5" = yeni "+5" mi?
> - Cevap:

> [!claude] Claude · 2026-10-29
> ## 6. Keywordler
> **U17** ⬜ **Keyword kategorileri.** Eski 4 tematik kategori (Background / Feature / Proficiency / Others). Yeni 3 işlevsel tip (meslek + advantage / doğrudan +SL ya da etki / sadece özellik) ([[NERRATIVE SYSTEM#Keywords]]). Başlangıç "6 keyword, 2-2-2"; eski oran "4 Background, 2 Feature, 1 Combat".
> - (a) 4 kategori başlık olarak kalır, her keyword'e yeni tip etiketi eklenir (iki eksen)
> - (b) Keywordler yeni 3 tipe göre yeniden dağıtılır, eski kategoriler kalkar
> - Ek: "2-2-2" hangi üç grup? Eski "4-2-1" oranı tavsiye olarak yaşasın mı?
> - Cevap:

> [!claude] Claude · 2026-10-29
> ## 7. Tokenler ve sayaçlar
> **U18** ⬜ **Token eşlemesi.** İçerik karşılaştırınca adlar çaprazlanmış gibi:
>
> | Eski | Eski işlevi | Yeni aday | Yeni işlevi |
> |---|---|---|---|
> | Uğur Jetonları | +3SL / reroll, sonra GM'e geçer, GM karşına kullanır | **İnspiration**? | destek al, ilerde kilit anda zorluk olarak döner |
> | İlham Simgeleri | GM ödülü, sahneye müdahale (tanıdık gardiyan, gizli tünel) | **Fluke**? | sahnenin gidişatını manipüle eder |
> | Devam Simgeleri | kritikte d6 "Yes and / No but" tablosu | **Turnout** | yes and, no but |
> | Talih Simgeleri | sadece Blind Luck keyword'üyle | — | — |
> | — | — | Değişim tokenleri | karakteri baştan kurar |
>
> - (a) Bu çapraz eşleme doğru, eski kurallar yeni adların altına girer
> - (b) Adlar aynı sırayla eşleşir (Uğur = Fluke, İlham = İnspiration), içerik yeni tanıma göre değişir
> - (c) Talih Simgeleri Blind Luck keyword'ünün kuralı olarak kalır / kalkar
> - Cevap:
>
> **U19** ⬜ **Karma ve Kargaşa.** Eski Karma = oyuncuya bağlı talih (d10 + KARMA, Events Table). Eski Kargaşa Sayacı (Pişmanlık puanı) = toplumun/dünyanın tepkisi. Yeni: "Karma, dünyanın tepki sayacı", yani tanım eski Kargaşa'ya benziyor.
> - (a) Yeni Karma = eski Kargaşa, eski Karma (Events Table) başka adla kalır
> - (b) Yeni Karma = eski Karma, Kargaşa ayrı sayaç olarak eklenir
> - (c) İkisi tek sayaçta birleşir
> - Cevap:
>
> **U20** ⬜ **Hedefler, hayaller, korkular.** Yeni sayaç: "büyük hayallerin dünya kurallarını ihlal edecek etkinliği ve aşil tendonu korkular". Eski: Goal Harvesting (Destiny / Dream / Mission + GM'in Setback / Spiral Down / Breaking Point tokenleri) ve Character Absolutes (+2 / +1 / +1 / -1 / -1 / -2 güç-zaaf). Not: Character Absolutes'un deseni yeni başlangıç stat dağılımıyla birebir aynı.
> - (a) Goal Harvesting hayaller sayacının altyapısı olur
> - (b) Character Absolutes korkular/zaaflar tarafı olur
> - (c) İkisi de ayrı sistem olarak kalır
> - Cevap:
>
> **U21** ⬜ **Exhaustion ↔ Tükenmişlik sayacı.** Eski Exhaustion bir durum (Stagger gibi -SL, dinlenince düşer, uykusuzluk / düşük esans ekler; Soul Surge overcast'te +2, Events Table'da +2). Yeni Tükenmişlik sayacı tempo/yolculuk sayacı, tersine çevrilince aftermath puanı.
> - (a) Aynı şey: eski Exhaustion yeni sayacın savaş/beden tarafı
> - (b) Ayrı ikisi: Exhaustion durum, Tükenmişlik sayaç
> - Cevap:

> [!claude] Claude · 2026-10-29
> ## 8. Beceri sistemleri
> **U22** ⭐ ⬜ **Beceri sistemleri ve Class'lar.** Yeni: "Classlar: Erikan seçiminin ardından alınır" (Ziran) ve "her beceri tek bir fantazi çekirdeğinden dallanır" ([[Style Notes]]). Eski: Soul Surge, Instrument Aide, Dream Weaving, Dark Heart (Kara Yürek), Invisible Organ (Repulsion?) "Others" keywordü olarak alınıyor; yeni keyword tip 3 ("büyü sistemi keywordleri") de buna uyuyor.
> - (a) Beceri sistemleri keyword olarak kalır, Class ayrı bir katman
> - (b) Her beceri sistemi bir Class olur
> - (c) Class = beceri sistemine giriş keyword'ü + ırk dışı paket
> - Cevap:
>
> **U23** ⭐ ⬜ **Beceri sistemlerinde ilerleme ve "MILESTONE" adı.** Soul Surge ve Repulsion'daki MILESTONE'lar (kademe ödülleri) ile yeni sistemin 44 milestone'u aynı kelime.
> - Bir beceri kademesi (ör. Soul Surge 4E) nasıl açılır? (a) progression milestone'unun bir adımı harcanarak (b) ESNC o seviyeye çıkınca kendiliğinden (c) başka
> - Beceri içindeki MILESTONE'lara yeni sistemde başka ad verilsin mi (Eşik, Kilit…)? Eski metin aynen kalır, yeni kuralda ne denecek?
> - Kara Yürek İlmi "Öz" diyor, diğerleri ESNC/Essence: yeni sistemde aynı havuz mu?
> - Cevap:
>
> **U24** ⬜ **Soul Surge HOT TAKE ↔ yeni ESNC formülü.** Eski notun: "Focus'u esans artışından ayır, sadece WP arttırsın". Yeni formül hâlâ `ESNC: Foc+WPB+Race`. (Notun diğer yarısı, Soul Surge'ün bir attribute'a attune olup THG/INT/CHR ile atılabilmesi, çelişmiyor: panoya kabul olarak girdi.)
> - (a) Yeni formül geçerli, HOT TAKE arşivde kalır
> - (b) HOT TAKE geçerli, yeni formülü sen güncelleyeceksin (Focus çıkar)
> - Cevap:

> [!claude] Claude · 2026-10-29
> ## 9. Erikanlar
> **U25** ⬜ **Vikos ve ateş.** Yeni ([[Style Notes]]): "Vikos ateşe değdiği an işi bitmiş demektir". Eski [[Vikos'Anel]]: Flammable, "yanma etkisi turda 2 artar". Derece farkı.
> - (a) Style Notes'taki sert hali geçerli, Flammable yeniden yazılacak
> - (b) Flammable mekaniği "işi bitmiş"in kural karşılığı sayılır
> - Cevap:
>
> **U26** ⬜ **Irk keyword paketleri ve başlangıç keywordleri.** Eski ırk sayfaları 10–16 keyword veriyor (Arik'Xea ~16). Yeni: başlangıçta 6 keyword, tam karakterde 24.
> - (a) Irk keywordleri ayrı, 6'ya sayılmaz
> - (b) Sayılır
> - (c) Irk paketi küçülür: birkaç çekirdek keyword + İstenen / Kaçınılması gereken durum, gerisi ırka açık seçenek
> - Cevap:
>
> **U27** ⬜ **Irk listesi kapalı mı?** [[Style Notes]]'taki liste: İnsan, Kharan, Bai, Orenn, Cam Erikan, Arik'Xea, İlkkan, Vikos'Anel, Kızıl Benizliler, Azothan. Eskide listede olmayanlar: Crystalines, Metal Erikan, Senea, Raw Binders, Seers of Tayhun, Shepherds, ve panodaki halklar (Çiğ Halk, Sebaz Halkı, Gün körü, Atmaca, Kül Azizi/Kızıl Deli, Deva Halkı, Soluk Benizliler…).
> - (a) Liste kapalı değil, eskiler de kabul (kural 1'e göre öyle varsayıldı)
> - (b) Liste kapalı, dışındakiler arşivde kalır
> - Ek: **Kızıl Benizliler** eskide hangisine denk? (Kül Azizi/Kızıl Deli? Soluk Benizliler? yeni mi?)
> - Cevap:
