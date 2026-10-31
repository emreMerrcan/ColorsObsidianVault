> [!claude] Claude · 2026-10-31
> # Actions
> Aksiyon ve savaş kuralları. Eski [[Combat Rulings]] ve [[Combat Specials]]'tan, [[Uyarlama Soru Listesi]] kararlarıyla çevrilerek geldi. Time shard yok (U11): savaş eski **tur + initiative** düzeniyle akar.
> Sayı çevirileri ([[Stats]]'taki genel kural): eski ±10 = ±1SL (U01), SL ölçeği aynı (U03), hasar / etki zarları aynı (U04), SB / TB / AGB… yeni bonusla birebir (U05). Çevrilen her sayının yanında eskisi parantezde.
> İşaretler: 🚩 karar bekliyor ya da çelişki · 🛠️ tasarlanacak (eskide boş, yarım ya da hiç yok)

> [!claude] Claude · 2026-10-31
> ## Aksiyon, test, SL
> - **Aksiyon:** zar istenen her şey. Savaşta zaman dar, varsayılan olarak bir anda bir aksiyon. Küçük işler (su içmek, orta boy bir şeyi itmek, uyuyan birine vurmak) zar bile istemeyebilir.
> - **Test:** d10 + attribute + skill = SL ([[Stats]]). GM bir **Difficulty Number (DN)** verir, SL'n onu geçmeli. Hangi attribute + skill'in atılacağını da GM söyler.
> - **Kritik (U02):** doğal **10** kritik başarı, SL ikiye katlanır. Doğal **1** kritik başarısızlık: saldırıyorsan silah elinden uçabilir, çelmelenip düşebilirsin. Kritikte Turnout tablosu ([[Tokens]]).
> - **Opposing Tests (U12, eski hali):** hamlen başka bir varlığınkiyle çarpışırsa ikiniz de atarsınız (sen vurmaya çalışıyorsun Combat'la, o kaçmaya AGL'yle). Yüksek SL başarır. İkisi de başarısızsa kimse bir şey alamaz. **İkisi de başarırsa ikisi de istediğini yapar**, yüksek SL'li yine de işini görür.
> - 🚩 DN'nin yeni ölçekteki tipik değerleri (kolay / orta / zor) hiçbir yerde yok. Eski SL tanımı (stat'ı geçtiğin her 10) d10'da kalktı, örnek DN'ler eski sayfada da yok.

> [!claude] Claude · 2026-10-31
> ## Savaş akışı (Steps of Combat + Initiative)
> U11: time shard'sız temel sistem bu. [[Stats#Pace]]'teki "Ruling Without Time Shards" örneği bu akışla oynanmış hali.
>
> 1. **Initiative.** Genelde ilk davranan ilk başlar. GM hangi stat'ın atılacağına karar verir: hızlı tepki gerekiyorsa AGL, dövüş ağır sosyal ipuçlarıyla başlıyorsa CHR ya da INT. Herkes atar, sırayla oynar.
>     - Opposing bir aksiyon olursa initiative'den bağımsız iki turunuz bağlanır, karşılıklı aksiyonlarınızı aynı anda yaparsınız. Opposing olmayan aksiyonlar kendi sırasını bekler.
>     - Planlı bir baskında oyuncular kendilerini sıraya, hatta ikili gruplara ayırabilir. GM düşmanları da kolaylık için öyle dizebilir.
> 2. **Aksiyonunu ve hedefini seç.** Saldırıyorsan bir vücut bölgesi seçebilirsin (Targeted Hit Locations), seçmezsen Random Hit Location.
> 3. **GM DN'yi verir** ve hangi attribute + skill'i atacağını söyler. Opposing test oluşuyorsa karşı reaksiyonu söyler ve onu da atar.
> 4. **SL'ni hesapla.** DN'yi ya da opposing testi geçtin mi bak. Kritik mi (doğal 1 / 10) bak, uygula.
> 5. **Etkileri uygula** (hasar vs.). GM sonucu ve dünyada nasıl yaşandığını anlatır.
> 6. **Tur sonu.** Sıranı bekle, döngü tekrar. Turunu bitirdiysen başkasına opposing testle tepki veremezsin.
>
> - Eski kurallarda "her tur", "sonraki tur", "turda bir" geçen her şey aynen geçer (Bleeding, Stagger, Concentration, Pace Borrowing, Momentum, Move Action, Revivify…).
> - **Forseen Paths** (Others keyword'ü): initiative'de iki kez, ilk ve son sırada oynarsın (aynı Pace havuzuyla). Bütün aksiyonların reaksiyon olarak da kullanılabilir ve düşmanın hamlesinden önce sayılır.
> - **Pace** (taban 10, aşım cezası, half action bedeli, Pace Borrowing): [[Stats#Pace]].

> [!claude] Claude · 2026-10-31
> ## Hareket (U14)
> - **MOV = AGLB × 2** metre: bir turdaki koşu mesafen (Running). **MOV/2** ortalama yürüme hızın.
> - Her tur **bir bedava Move Action**. İkincisi bütün Pace'ini alır (Outpacing Predator'la 7 Pace).
> - Bir turda doğal yolla **asla MOV×2'yi geçemezsin**.
>
> | Hareket | Mesafe |
> |---|---|
> | Koşma (Running) | MOV |
> | Uçma | MOV × 2 |
> | Sürünme | MOV / 4 |
> | Tırmanma | MOV / 8 |
> | Dash (half action) | +MOV / 2 |
> | Jump (half action) | STRB/2 ya da AGLB/2 metre, uzunluk ve yükseklik |
>
> - **Yarış:** iki kişi birbirini geçmek için koşarsa MOV'ları opposing testlerine bonus olarak eklenir.
> - Örnek (AGLB 4 → MOV 8): Dash 4 m · bir Move Action 8 m · ikinci Move Action (tüm Pace) toplam 16 m. Dash bunun üstüne eklenmiyor, 16 tavan.
> - 🚩 Irk formüllerinin çoğu MOV için `AB` diyor, bu evrensel ×2'yle çelişiyor: [[Style Notes#Erikanlar]].

> [!claude] Claude · 2026-10-31
> ## Hasar ve vuruş bölgeleri
> **Hasar hesabı:** her silah ve hasar türünün bir değeri var, SL'nle hesaplanır.
> - Başarılı Uzun Kılıç vuruşu, `2SL+4`, 3SL attın: 3×2+4 = **10**.
> - Kritikte SL ikiye katlanır (3 → 6): 6×2+4 = **16**.
> - Sonra düşmanın o bölgedeki direnci düşülür. 6 RES'li göğüslük: 16-6 = **10**.
> - 🚩 Eski örnek Uzun Kılıç'ı `2SL+4` alıyor, silah listesinde `2SL+5`.
>
> **Targeted Hit Locations:** belirli bir yeri hedeflersen vurmak zorlaşır, her bölgenin geçilmesi gereken bir SL eşiği var. Hedefi vurmak niyete göre güçlenmiş etkiler doğurabilir.
>
> | Bölge | SL |
> |---|---|
> | Kafa | -3SL |
> | Kollar | -2SL |
> | Gövde | -1SL |
> | Bacaklar | -2SL |
>
> **Random Hit Locations (U02):** yer söylemezsen bu tablo. Ayrı bir **d10** atılır (eski "d100'ü ters çevir" kalktı). Tempo için çoğu zaman yok say, her karaktere tek bir kaba RES değeri ver.
>
> | d10 | Bölge | Eski d100 oranı |
> |---|---|---|
> | 1 | Kafa | %10 |
> | 2–3 | Sol kol | %18 |
> | 4–5 | Sağ kol | %17 |
> | 6–8 | Gövde | %35 |
> | 9 | Sol bacak | %10 |
> | 10 | Sağ bacak | %10 |
>
> - 🚩 Taslak, [[Yeni Sistem İnşa Panosu]]'ndan. Onay bekliyor (gövde burada %30, eskide %35).

> [!claude] Claude · 2026-10-31
> ## Kuşatma, konsantrasyon, gizli saldırı, momentum
> - **Flanking:** yakın dövüşte rakibi kuşatan her müttefik için **+2SL** (eski +20). 3 kişi 1 kişiye: hepiniz +4SL (eski +40). 3'e 2: hepiniz +2SL.
> - **Disabilities:** ortam, zemin, hava, yara ya da düşmanın durumu dezavantaj verebilir.
> - **Concentration:** tur boyu hareket etmez, başka aksiyon almazsın. Bölünmeden geçen bir turdan sonra sonraki turdaki hamlene **+3SL**.
> - **Stealth Attacks:**
>     - Savaşı başlatan bir stealth saldırısı takıma sürpriz turu verir.
>     - Başarılı stealth saldırısı **otomatik kritik**.
>     - Düşman genel yerini aklında tutuyorsa stealth olmaz: saklan, yer değiştir.
>     - Görülmeyen ve beklenmeyen saldırılar stealth sayılır. Göz önünde Deception'la sahte bir hamle yapıp stealth saldırısı da kazanabilirsin.
>     - Stealth zarına düşmanın **pasif INT**'i dezavantaj olarak girer. Seni zaten görüyorlarsa ve fake out yapıyorsan pasif **AGL** ya da **CHR**.
> - **Momentum Actions:** bir aksiyonda ilk kez **5SL üstü** atarsan bedava bir half action alırsın. İlk aksiyona makul biçimde zincirlenmeli, hemen ardından olmalı.
> - 🚩 Momentum iki yerde iki türlü: burada genel kural "5SL üstü, ilk kez", [[Feats#Keywords]]'teki Momentum Actions keyword'ü "6SL+, turda bir". Biri genel kural, diğeri keyword'ün güçlendirilmiş hali mi?

> [!claude] Claude · 2026-10-31
> ## Durumlar
> | Durum | Kural |
> |---|---|
> | Düşme | AGLB ya da THGB metreden yüksek her düşüş metre başına 4 hasar. Düzgün düşemiyorsan (baygın, fırlatılmış) metre başına 6. |
> | Kanama | Üst üste biner. Her tur 1 hasar, sonra kendini 1 azaltır. Bazı yaralar tedavi edilene kadar sınırsız kanatır. |
> | Yanma | Söndürülene kadar her tur +1 büyür (Vikos'ta +2, Flammable). Her tur yanma birimi kadar hasar. Başlangıç birimi verilir. Söndürme aksiyonu SL+2 kadar azaltır. |
> | Stagger | Her birim bütün zarlara -1SL, -2 Pace, -1 MOV. Her tur 2 azalır. |
> | Stunned | Aksiyon, reaksiyon ya da hareket yok. |
> | Grapple / Ensnare | Stat check'le kurtulmaya çalışırsın. Verilen DN'yi geçersen kurtulursun ya da benzer şekilde kontrolü alırsın. Normal grapple'da DN tutanın STRB'si. |
> | Zehir ve kurtulunabilir durumlar | Bazıları ancak verilen DN'li stat check'i kaçırınca işler, bazıları ortalama sonuç için birden çok zar ister, bazılarının etkisi SL'ne göre azalır. Ör. 3 DN'li zehir: 3 ya da altı SL'de etki eder. |
> | Exhaustion | Artık **Tükenmişlik sayacı**'nın beden tarafı (U21): [[Tokens]]. |
>
> - 🚩 Düşme eşiği "AGB or THB": hangisi yüksekse mi?
> - 🛠️ **Daze / Afallama** her yerde geçiyor (Afalla silah özelliği, Soul Surge, Instrument Aide, Hit to Stun) ama durum olarak tanımlı değil. Sadece Stunned var. Afallamış biri ne kaybeder?

> [!claude] Claude · 2026-10-31
> ## Yaralar, kırıklar, sürünme
> - **END sıfır:** gündelik bir dövüş Endurance sıfırlanınca biter. Kaçmamak ya da bayılmamak için WP ya da THG save'i, **+2SL** (eski +20). Ölüm kalım durumlarında bu zarlara **+5SL** (eski +50).
> - **Health hasarı:** Health'ine her hasar aldığında Lingering Injuries tablosunda at.
> - **0 Health:** ayrıca sürünme durumuna düşmemek için bir save daha.
> - **Sıfırın altı:** aksiyonlarına **-1SL** (eski -10), her hasarda Critical Fractures'da at. Health'inin negatif eşitine inersen ölürsün.
> - **Crawling Condition:** 0 Health'te yere düşersin, sadece sürünerek hareket edersin. Her tur 1 **Revivify** puanı: 2 puanla bir aksiyon alırsın, 5 puanla kendi başına ayağa kalkarsın (TB endurance'la). Bayılana ya da normal Health'inin negatifine inene kadar sürünme durumunda kalabilirsin.
> - 🛠️ **Lingering Injuries** ve **Critical Fractures** tabloları hiçbir yerde yok (Decapitate keyword'ündeki "Critical Wounds" da). [[Roll Tables]]'taki Physical / Severe Physical Conditions başlangıç olabilir.
> - 🚩 "5 puanla TB endurance'la ayağa kalk" belirsiz: THGB kadar END'le mi kalkıyorsun, yoksa THGB'lik bir test mi?

> [!claude] Claude · 2026-10-31
> ## Half Actions (U13, eski haliyle)
> - Half action (hamle) gerçek bir aksiyon harcamadan ve ceza almadan alınır. **2 half action = 1 full action.**
> - Bedeli **2 Pace**, ardışık her half action'a **+1 Pace** (Double Step ve Many Gestures bu cezayı kaldırır).
> - Kendi hamleni uydurabilirsin; stat check'i ve etkisi yaratıcılığına ve şartlara bağlı.
> - **Opportunity Reaction:** biri tepki menzilinden (1 m) geçerken ona karşı doğrudan bir reaksiyon hamlesi yapabilirsin: çelme, grapple, shove, stun…
>
> | Hamle | Etki |
> |---|---|
> | Block | STR + fiziksel check ile gelen saldırıya karşı koy. Geçersen objenin direncini saldırıya uygula. Silahlar PACE - 1 kadar bloklar. Kalkanların kendi Pace bedeli olabilir. |
> | Soak | THG + Fortitude: SL kadar hasarı Health'e işlemeden savuştur. Vuruş etkileri yine uygulanır. |
> | Dodge | AGL + fiziksel check: kaç, kendi SL'ni düşman saldırısının SL'inden düş. |
> | Dash | MOV/2 metre ek hareket. |
> | Jump | STRB/2 ya da AGLB/2 metre uzunluk ve yükseklik. |
> | Shove | STR + Athletics: bir şeyi SL metre kenara savur (kütle farkına göre). |
> | Grapple / Snare | Pasif STR'ını geçerek bir şeyi hareketsiz tut. Onu hedef alanlar **+2SL** (eski +20). Kurtulmak için rakip opposing'de senin SL'ni geçmeli. |
> | Hit to Stun | Silahının afallatma eşiğine 2SL indirim. |
> | Aim | Hareketi feda et, +1SL. Manuel hedeflemede +2SL daha. |
> | Shout | CHR + Expression / Deception: korkut, ürküt ya da sahte niyet göster, avantaj al. Pasif CHR'ı ya da contest'i geçmeli. |
> | Aid | Avantajlarını paylaşarak başkasına +SL ver (taban +1SL). Bkz. [[Feats#Help]]. |
> | Analysis | Alanı, durumu ya da düşmanı INT ya da CHR'la analiz et. |
> | Ready Action | Bir aksiyon ilan et ve tut. Saldığında initiative'e bakmadan öncelikle olur, düşmanı keser; +1SL. |
> | Lock In | Anlık odakla bir aksiyona +1SL. |
> | Counter Diversion | Gelen saldırıya silahınla saldırı at; düşmanın SL'i senin SL'in kadar azalır. |
> | Counter Block | Gelen saldırıya silahınla saldırı at; başarırsan silahın RES'ini zırhının üstüne ekle. |
>
> - 🚩 Block ve Dodge'daki "fiziksel check": yeni listede PHYSICAL grubu (Acrobatics / Athletics / Swiftness / Fortitude) içinden duruma göre mi?
> - 🚩 Block: "silahlar PACE - 1 kadar bloklar" ama silah özelliklerinde "Blok (X): X RES sağlar" da var.
> - Ready Action eski Stances bölümünde biraz farklı tekrar ediyor: +1SL, düşmanı kesmek için ya da sonraki tur kullanmak için.

> [!claude] Claude · 2026-10-31
> ## Stances ve Dual Wielding
> Stance, karakterin hareketlerinde neye öncelik verdiğini gösterir. Kaplumbağa gibi güvende durup saldırıda fazla açılmıyorsan Defencive Stance'tesin. GM izniyle oyuncu kendi stance'ını uydurabilir.
>
> | Stance | Etki |
> |---|---|
> | All-Out | Saldırına +2SL, ama bütün rakip saldırılarına da +2SL. |
> | Defencive | +3 RES, ama bütün rakip saldırılarına +2SL. |
> | Evasive | Rakip saldırılarına -2SL, ama onlardan +SL hasar alırsın. |
>
> - **Dual Wielding:** Ambidextrous ve proficiency'yle iki silah tutarsın, ekstra aksiyonlara **+1SL** (eski +10).
> - 🚩 Dual Wielding üç yerde üç türlü, bkz. [[Stats#Pace]]'teki not.

> [!claude] Claude · 2026-10-31
> ## Silah özellikleri
> Her silah yaratıcı kullanılabilir: mutfak bıçağıyla sıraya dizilmiş hedefleri tek savuruşta kesmek, tüfeğin dipçiğiyle kafaya vurmak. Bıçak alan silahı olur, keskin nişancı tüfeği kafa ezen bir çekice döner. Aşağıdakiler sık kullanılacak örnek hamleler.
> Özel hamleler durumsaldır, her zaman iyi sonuç vermez: kılıcın kabzasıyla afallatmaya çalışırsın ama hazır bekleyen bir düşmana denersen opposing testte büyük dezavantaj yersin. Savaşta rol yapmanın ödülü, savaşa atılacak beceriler değil.
>
> **Yakıncı silahlar**
>
> | Özellik | Etki |
> |---|---|
> | Aksiyon Temposu P(X) | Kullanınca X Pace harcar. |
> | Afalla (X) | X SL ve üstü düşmanı afallatır. X'i 3SL daha aşarsan sersemletir. |
> | Alan Etkisi (X) | Hedefin etrafında X büyüklüğünde bir alanı etkiler. |
> | Süpürücü Kenar (X) | Bir savuruşta birçok rakibe azalarak vurur. X her çarpmada törpülenen hasar. Taban 10. |
> | Deşergeçer (X) | Rakibin X kadar direncini yok sayar. |
> | Zırh Kıran (X) | Hedefin RES'ini geçip zırh senin hasar tipine hassassa X RES kırar. |
> | Zayıf Nokta (X) | Zırhın zayıf nokta eşiğini X düşürür. |
> | Durum (X) | Söylenen etkiyi uygular: kanama / zehir / yakma X tur, sersemletme / afallatma X SL'i geçerse. |
> | Tutucu (X) | Rakip tutulup kalır, her tur zar atar, X SL'i aşana dek sabit. |
> | Öteleme (X) | Rakibi silahınla ötelersen +X SL. |
> | Kopar / Kır (X) | SL X'i geçerse vurduğun parçayı koparır ya da ezip kırarsın. |
> | Blok (X) | Bu silahla blok X RES sağlar. |
>
> **Uzakçı silahlar**
>
> | Özellik | Etki |
> |---|---|
> | Hasar Tipi | Delici, Ezici, Kesici, Patlayıcı… |
> | Atış (X) | Turda X atış yapar ve ona göre Pace harcar. |
> | Değişim Süresi R(X) | Hazne değiştirmek X Pace. |
> | Çabukluk (X) | Çoklu aksiyonlara X SL ekler. |
> | Hazne (X) | Bir doldurmada X atış. |
>
> **Mermiler:** silahın taban hasarına ve etkilerine eklenir (kanatıcı uçlu ok, yanıcı maddeyle dolu kurşun…). Delici Ok: Delme 2 · Kanatıcı Ok: Kanama 2 · Çelik Başlı Ok: +1 hasar · Patlayıcı Mermi: +3 hasar.
>
> - 🛠️ Silah satırlarında geçen ama tanımlanmamış özellikler: **Çoklu Hamle** (Gürz, Kırbaç), **Darbe** (kalkanlar), **Kanama**, **Delme**, **Kanat** (Kaos Bıçakları; Kanama mı?).
> - 🚩 Aynı özellik farklı yazılmış: Afalla / Afallat, Zırh Kıran / Zırhkıran, Deşergeçer / Deşergeç, Süpürücü Kenar / Süpürücü (Oren'deki "Sweeping"), Tutucu / Tut, Alan Etkisi / Alan Etkili. Aşağıdaki tabloda hepsini tanım listesindeki adla yazdım.

> [!claude] Claude · 2026-10-31
> ## Silahlar ve kalkanlar
> Menzil: K kısa, O orta, U uzun, M menzilli. "Aralık" eski sayfadaki hasar aralığı, olduğu gibi. Pace ve reload değerleri aynen (U10).
>
> **Yakın dövüş**
>
> | Silah | Menzil | Hasar | Aralık | Özellikler |
> |---|---|---|---|---|
> | Yumruk ya da Tekme | K | SB-2 | — | P(2), Afalla 4 |
> | Kılıç | O | SL+4 | 5-7 | P(4), Süpürücü Kenar 6, Zayıf Nokta 1, Delme 2 |
> | Uzun Kılıç | U | 2SL+5 | 6-10 | P(6), Süpürücü Kenar 4, Zayıf Nokta 1, Kopar 5 |
> | Koca Kılıç | U | 3SL+6 | 9-15 | P(11), Süpürücü Kenar sınırsız, Kopar 2, Zırh Kıran 2, Cüsse 4 |
> | Balta-Mızrak | M | 2SL+2 | 6-10 | P(8), Kopar 4, Öteleme 2, Süpürücü Kenar sınırsız |
> | Tırpan | O | 2SL | 6-10 | P(6), Kopar 2, Süpürücü Kenar sınırsız |
> | İnce Kılıç | U | 2SL+3 | 7-11 | P(5), Süpürücü Kenar 4, Zayıf Nokta 2, Kanama 5 |
> | Topuz | U | SL+4 | 6-10 | P(8), Süpürücü Kenar 5, Zırh Kıran 1, Afalla 3 |
> | Gürz | O | SL+7 | 8-12 | P(5), Çoklu Hamle +1SL (eski +10), Zırh Kıran 2, Afalla 3 |
> | Kaos Bıçakları | M | 3SL+2 | 3-11 | P(5), Süpürücü Kenar 6, Kopar 5, Kanat 3 |
> | Zincir Mızrak | U | SL+3 | 5-9 | P(3), Deşergeçer 3, Süpürücü Kenar 6 |
> | Biçer Makas | O | 2SL+2 | 3-10 | P(5), Kopar 2, Alan Etkisi: karşısını koparır |
> | Çekiç | O | SL+6 | 7-11 | P(5), Zırh Kıran 2, Deşergeçer 2, Afalla 3 |
> | Rapier | O | SL+2 | 2-6 | P(3), Zayıf Nokta 2, Deşergeçer 2 |
> | Sopa | O | SL | 1-5 | P(4), Öteleme 3, Afalla 4 |
> | Muşta | K | SB | 2-6 | P(2), Afalla 5 |
> | Mızrak | M | SL+4 | 5-9 | P(5), Deşergeçer 3, Öteleme 2 |
> | Balta | O | SL+6 | 7-11 | P(5), Süpürücü Kenar 6, Kopar 3, Zırh Kıran 1 |
> | Cellat Baltası | O | SL+10 | — | P(9), Kopar 3, Zırh Kıran 2 |
> | Kütük | O | SL+2 | 3-7 | P(3), Afalla 3 |
> | Pala | O | SL+4 | 5-9 | P(4), Kopar 5 |
> | Kırbaç | M | SL+2 | 3-7 | Tutucu 2, Çoklu Hamle +2SL (eski +20) |
> | Bıçak | K | SL | 1-3 | P(2), Kanama 2 |
> | Hançer | K | SL+2 | 4-12 | P(3), Kanama 4, Deşergeçer 2 |
>
> **Fırlatma, yaylı ve ateşli**
>
> | Silah | Menzil | Hasar | Aralık | Özellikler |
> |---|---|---|---|---|
> | Fırlatma Bıçağı | K | SL+1 Delme | — | P(2) |
> | Cirit | 0 | SL+3 Delme | — | P(3), R(1) |
> | El Arbaleti | O | SL+8 Delme | 9-13 | P(3), R(5) |
> | Kurmalı Arbalet | U | 3SL+8 Delme | 11-23 | P(4), R(8) |
> | Ok ve Yay | O | SL+5 Delme | 6-10 | P(2), R(3) |
> | Sapan | O | SL+2 Ezme | 3-8 | P(3), R(2) |
> | Çekmeli Sapan | O | SL Ezme | 1-5 | P(2), R(2) |
> | Misket Tabancası | K | 2SL+2 | 4-12 | P(2), R(3) |
> | Misket Tüfeği | U | 2SL+6 | — | P(4), R(4) |
> | Çiftteli Tüfek | K | SL+8 | — | Atış 2, P(4), R(4) |
> | Alev Püskürten | K | SL+2 | 3+7 | Atış 1, P(8), R(16), Hazne 5, Süpürücü Kenar 3, Alan Etkisi 1 |
> | Basınç Tüfeği | M | 4SL+7 | 11-27 | P(6), R(6) |
> | KNDS Full-Auto | U | 3SL+5 | 8-20 | Atış 10, P(10), R(4), Hazne 30, Çabukluk +1SL (eski +10) |
> | Top | U | 2SL+30 | 22-30 | P(8), R(20) |
> | Balista | U | 3SL+18 | — | P(6), R(10) |
> | Çığlık Tabancası | K | SL | 1-4 | Atış 1, P(6), R(8), Hazne 2, Durum: Sersemlet 3, Alan Etkisi 3 |
>
> **Kalkanlar ve plakalar**
>
> | Kalkan | RES | Özellikler |
> |---|---|---|
> | Tahta Plaka | 4 | — |
> | Metal Plaka | 5 | — |
> | Kol Kalkanı | 7 | P(2), Darbe: SB |
> | Çelik Kalkan | 10 | P(3), Darbe: SB+2 |
> | Duvar Kalkan | 13 | P(4), Darbe: SB+4 |
>
> - 🚩 Kırbaç'ın P değeri yok. Cirit'in menzili "0" (K mı?).
> - 🚩 Bazı aralıklar formülle tutmuyor (Kılıç `SL+4` 5-7, Hançer `SL+2` 4-12, Alev Püskürten "3+7"), bazılarında aralık yok.
> - Eski sayfanın altında taslak bir kategori satırı var: "Tek Elli, Çift elli · Ezme, Delme, Kesme · Boyut: S, M, L". 🛠️ Silahlara el sayısı ve boyut etiketi eklenecek mi?

> [!claude] Claude · 2026-10-31
> ## Menzil
> - **Yakıncı silahlarda** rakibin silahıyla aradaki menzil kademe farkı başına opposing teste +1.
> - **Nişancı silahlarında** her kademe +20 m menzil. Menzil ötesine atış kademe başına **-3SL** (eski -30). Her 5 m yükseklik +10 m menzil.
> - Sniper keyword'ü: Aim'le menzil sınırının bir kademe üstüne atış.

> [!claude] Claude · 2026-10-31
> ## Zırhlar
> **Direnç:** koruduğu yüzeye gelen hasarı X azaltır. Zırh, hassas olduğu hasar tipiyle kritik yerse yıpranır (-2 RES) ve işlevsiz kalabilir.
>
> | Sınıf | RES | Örnek |
> |---|---|---|
> | Doğal Zırh | türe bağlı | her canlının deri direnci |
> | Hafif Zırh | +2 | deri zırh, yastıklama |
> | Orta Zırh | +4 | bronz zırh |
> | Ağır Zırh | +6 | çelik zırh |
> | Tam Zırh | +8 | katmanlı, yüksek işçilik |
> | Aşılmaz Zırh | +16 | emsalsiz sağlamlıklar |
>
> **Zırh özellikleri**
> - **Zayıf Nokta (ZN X):** saldırı X SL'i geçerse zırhın koruması yok sayılır.
> - **Katman:** başka zırhların altına giyilebilir.
> - **Gürültü:** Stealth ve benzeri zarlara **-2SL** (eski -20).
> - **Hassas (K, D, E):** bu hasar tipine hassas. O kaynaktan 1 fazla hasar alır, iki kat yıpranır, Zırh Kıran'dan etkilenir.
> - **Cüsse (C X):** X kadar STRB ya da THGB'n yoksa bu zırhı giyemezsin (U05: yeni bonusla birebir).
>
> | Zırh | RES | Özellikler |
> |---|---|---|
> | Yün Giysi | +1 | Katman, Hassas (K) |
> | Deri Zırh | +2 | Katman, Hassas (K) |
> | Kadife Sargı | +3 | Katman, Hassas (D) |
> | İnci Cilt | +4 | Katman, Hassas (E). İradeye göre biçimlenebilir. |
> | Örtü Pelerin | +1 | Katman. Dodge ve Stealth aksiyonlarına +1SL. |
> | İlişen Kabuk | +5 | Katman |
> | Zincir Yelek | +3 | Gürültü, Katman, Hassas (D) |
> | Pullu Yelek | +4 | Gürültü, Katman, Hassas (D) |
> | Yaşar Kabuk | +4 | Katman, Hassas (K). Belirli bir hasar tipine +2 RES. |
> | Eklips Zırh | +7 | Cüsse 4, Gürültü, Hassas (D, E). Hasar 1 RES kırar ama hasarı karşıya yansıtır. |
> | Bronz Zırh | +6 | Cüsse 4, ZN 5, Hassas (E) |
> | Çelik Zırh | +8 | Cüsse 5, ZN 6, Hassas (E) |
> | Menor Zırhı | +10 | Cüsse 5, ZN 8, Hassas (E) |
> | Aydın Zırh | +8 | Cüsse 5, ZN 7, Hassas (D, E). Öz harcayarak kendini onarır. Turda 18+ vurulursa kalıcı hasar alır. |
> | Kathrania Zırh | +14 | Cüsse 6, ZN 10. Zırh Kıran'dan etkilenmez. Lore: [[Far'Yadox]] |
>
> - 🚩 Sınıf tablosu eşyalarla çelişiyor: sınıfta Orta = bronz +4, Ağır = çelik +6; listede Bronz Zırh +6, Çelik Zırh +8.
> - 🚩 Hassas'taki K, D, E: Kesme, Delme, Ezme diye okudum (sayfa açmıyor).

> [!claude] Claude · 2026-10-31
> ## Boyut sınıfları
> | Sınıf | Metre | Örnekler |
> |---|---|---|
> | Gargantuan | 20–100 | Öyle Böyle, Torma, Sharaa |
> | Collosal | 10–20 | Tasarımcı, İhtişamlı Patikacı, Khass'Orothul |
> | Giant | 5–10 | Oren, T-Rex, fil |
> | Large | 3–5 | Kiz, ayı, İlkkan |
> | Medium | 1,5–3 | İnsan, Xea, kaplan |
> | Small | 0,5–1,5 | İne Sinen, çocuk, köpek |
> | Tiny | 0–0,5 | peri, fare, kedi |
>
> - Oren'in Brutal Proportions'ı boyut farkını kullanıyor: küçükler onun saldırılarını çok daha kolay bloklar / kaçar. 🛠️ Boyut farkının sayısal etkisi (kademe başına ±SL?) tanımlı değil.
