https://interfaceingame.com/games/?genres=card-game
# Tanımlar
Oyun kullanacağın desteleri seçmek üzerinden el oluşturur. Bir deste derlemek yerine, oyun başında ve esnasında kullandığın desteleri belirleyerek onların haznesinden rastgele seçimler yaparsınız. Bir oyun seansı esnasında rakiple aynı deste hazneleri tüketilir. Eğer aynı deste kullanılıyorsa iki kat hızlı tükenir, içerideki ender kartları çekmek değerli bir getiri olur.
### Oyun Alanları
İlki maç dışı alan yani, ana menü, eşleşme kurma ve giriş kısımlarıdır. İkincisi hazırlık alanıdır. Tarafların destelerini seçtiği, maç öncesi ve raunt arasındaki stratejik planlama aşamalarıdır. Diğeri de masa alanıdır. Burada kartlar yerleşir, aksiyon yaşanır ve bir taraf rauntun galibi olana dek maç devam eder.
### Oyun zaman tanımları:
* Maç: Eşleşme anından ana menüye dönülene kadarki oyuna dahil tüm zaman dilimini kapsar.
* Raunt: Bazı modlar birden fazla raunta sahiptir. Her raunt farklı masalarda yaşanır, sıfırdan kartlar çekilir, puanlar sıfırdan başlar ve kazanma şartına erişilince raunt sona erer. Çok rauntlu modlar, sonraki raunta geçerken tek rauntlu modlar maç sonuna erişir.
* Tur: Bir raunt içerisindeki her bir oyuncu sırasına denir. Oyuncunun hamlelerini gerçekleşip nihayet aksiyon sırasını diğer oyuncuya devrettiği zaman dilimidir. Bu bir oyuncudan diğerine geçmek suretiyle kazanma şartına erişilene dek devam eder. Oyuncu efektleri için tur sayımı oyuncu turu sayılarak yapılır. Örneğin: Oyuncu ilk 3 tur 2'şer kart çeker denildiğinde, bu o oyuncunun tamamladığı turlar sayılarak hesaplanır. Örneğin: Oyun 8 tur limitine gelince neticelenir dendiğinde bu, iki oyuncunun da dörder tur almasıyla değil, iki oyuncunun da sekizer tur almasıyla gelinen bir noktayı simgeler.
	Turun içerisindeki akış şu şekildedir:
	1- Turun oyuncuya geçtiğinin ilanı ve taraf izinlerinin işlenmesi, animasyonların oynaması.
	2- Tur başı etkilerinin tetiklenmesi.
	3- Oyuncunun kart çekmesi. Hakkı kadar kart oynaması veya paslaması.
	4- Kartların Turluk ve Hamle'lerinin kullanılması. Kurulum Sekansının ele alınışı. Kartların hareket etmesi.
	5- Tur sonu etkilerinin tetiklenmesi. Oyuncu turunun sonlanması.
* Mutlak Tur: İki oyuncuların turları toplamı, yani gerçekte gelinen tur sayısını temsil eder.
* Aksiyon: Bir oyuncunun tur içinde aldığı her bireysel aksiyona denir. Bu kart yerleştirmek, çekmek, hamle kullanmak, hareket etmek vs. olabilir. Aksiyonlar tükenince ya da pass geçilince oyuncu turu sona erer.
### Elementler
#### Kartlar
- Unit Cards: Standart birlik, masaya konur, hareket hakkında ve hamlelere vesaire sahiptir. Canı bitince ölür gider.  
- Attachment Cards: Bu kartlar Parazit eklentisine sahiptir ve başka bir karta yapışarak ona fazladan beceriler, pasifler, tetiklemeler ekleyebilir. Bir sahne varlıkları yoktur ve etkilerini KONAKları aracılığıyla gerçekleştirirler. Örnek: "Konak saldırdığı hedefi öldürürse bir kart çekersin" veya "Konağın vuruşları kanatırr. Eğer zaten kanamakta olan bir rakibe vurursa kanama bitişik rakiplere de uygulanır."
- Event Cards: Bu kartlar masada bir slota bırakılamaz, canları da yoktur zaten. Oynandıkları anda bir şey tetikler ve yok olurlar, ölmezler de. Büyü gibi fonksiyon gösterirler.
- Dream Cards: Bu kartlar masada bulunmaz ve masanın kenarındaki ayrı bir bölgede gözükürler. Oyuncunun rüya kartı yerleştirebileceği üç slot vardır ve fazlasını eklemeye çalışınca o slottaki kartı yok ettirir. Oyunu kapsayan kuralların değişimini temsil ederler. Üzerlerinde sayaçlar bulunabilir, belirli olaylarla tetiklenebilir veya aksyionlara reaksyion gösterebilirler. Puanları ve hasar işlemlerine dayalı attribute ları yoktur. Örneğin: Aydın Cennet kartı: Ölen kartlar ölüler destesine düşmek yerine onun haznesinde toplanır. Oyuncu 30 puana eriştiğinde, her tur o hazneden bir kartı puanını yenileyerek oynar. Masada bulunan, öldürülebilir bir şey değil, kapsayıcı, şarta bağlı bir eklenti gibi. Ya da mesela: Canavar Tanrı Kuvar: Conditional bir kart olarak başlar ve "6 düşman ölürse bu tur masaya inerim" gibi bir tetiklemeye sahiptir. Masaya indiği tur çok güçlü beceriler kullanır ve o turun sonu tekrar kurala dönüşerek döngüsüne devam eder. Bu ikisi çok ekstrem örnekler. "Tur başı, masadaki en düşük canlı dosta +2 veririm" kadar basitte olabilir bu kartlar.
- Hazard Cards: Kondukları slotu özelleştiren kartlardır. Masada bir birim gibi var olmak yerine o slota bir şartlanma eklerler. Bazı slotları erişilemez kılabilir, alan etkili efektler uygulayabilir veya tuzaklar devreye sokabilirler. Arenanın alanını değiştirmeleriyle bilinirler. Kapladıkları slotları doldurmazlar, yani birlik kartları onlar yokmuş gibi alanlarında yürünebilir. Örnek: "Yanlamasına üç kare koruluk olur. Koruluktaki düşmanlar içeride bulundukça Sustur etkisi altındadır." veya "Bu slot bir portal sayılır. Portal slotunda bulunan kartlar başka bir portal slotuna mesafe gözetmeksizin hareket edebilir (ışınlanma)" veya "Slot mayına dönüşür. Bir birim yakınına hareket edilmesi halinde patlayarak çevresine hasar uygular."

Kart yaşam döngüsü destede başlar. Çekim ile oyuncunun eline ulaşır. Burada gözden geçirilebilir ve bazı durumlarda masadaki bir kart tarafından etkileşime geçilebilir. Masada bir konum alarak oynanır, ardından tipine göre davranışını sergiler. Döngünü sonunda ya desteye geri karıştırılır, ya da ölüm ile ölüler destesine düşer.
#### Eklentiler (Conditions)
Nicelik ve nitelik arasındaki fark, biri temel parametrelerin değerlerini değiştirirken diğeri temel becerilere ekstra etkiler ekler. 
Nitelik ve Tetikleyiciler arasındaki fark, örneğin bir eklenti "Vuruşta rakibin desteğine +1 vur" deseydi nitelik, "Rakibin puanını kırınca şunu yap" deseydi tetikleyici olurdu.
Nitelik ve Etkileyici arasındaki bir farksa: Sarsıcı (nicelik eklentisi) sahibi olan kart rakiplerine Sersemlet uygularken, Sersemlet (etki eklentisi) mevcut olduğu sürece o kartın aksiyonlarını kısıtlar.
- Nicelik Eklentileri: (Attribute) Kartların sahip olduğu parametreleri arttıran veya azaltan eklentiler. Örneğin, Saldırılar +1 bitişik rakibe seker, +1 kıvılcım yenilenmesi, +1 hasar/iyileşme, +1 zırh, +1 hareket hakkı sağlayan Hızlı, alınan hasarları ikiye katlayan Zayıf, alınan hasarı engelleyen Zırh gibi.
- Nitelik Eklentileri: (Feature) Kartı özel etkileşimler sunarak değiştiren eklentilerdir. Örneğin: Her tur başı can yenilenmesini sağlayan Yenilenme, saldırıların sersemletme uygulamasını sağlayen Sarsıcı, kartın tur sonu ölmesini sağlayan Geçici, rakibe puan üstünlüğü sağlanınca hedef alınamazlık sağlayan Korkunç, saldırılar kadar can yenilemeyi sağlayan AÇ GÖZLÜ, kartın başka bir karta yerleşmesini sağlayan PARAZİT gibi.
- Tetikleyiciler: (Trigger) Belirli durumları gözlemleyerek onların karşılanması halinde özel etkiler çağırırlar. Örneğin: Evrim, bir rakibin alt edilmesi durumunda eklentilerinin çalınmasını içerir. Saldırı yapmadan turun sonlanması durumunda sonraki tur hedef alınamazlık sağlayan Gizli. Cinnet, kartın puanı yarıdan düşükse uyguladığı etkiler +1 artar. Kartın ölümü geldiğinde son bir kere turluk kullanmasını sağlayan Hortlak.
- Etkileyiciler: (Effector) Doğrudan davranış içerisindeki eklentiler. Bir kartın üzerine konumlanır ve bir davranışta bulunur, genelde bir tetiklenme veya tur sayacının netielenmesiyle son bulurlar. Kanama etkileri, sersemlemeler veya hedefleme işaretçileri bunlara dahildir.
#### Desteler
- Desteler: (Default Deck) Standart deste. Oyun başlangıcında seçilir, komşuları bulunur. Oyun esnasında tercih üzerine kart çekilebilir. Tükenebilirler.
- Bridge Destesi: (Bridge Bundle) İki destenin kombinasyonuyla erişilebilen ve ikisinden kart çekerken bundan da çekme ihtimalin bulunan kesişim alanlarıdır. Örneğin: Çoban ve Menor havza destelerini seçtiysem, onların temalarını barındıran özel 3 kartın oluşturduğu bir Hücre Destesi'ne de erişebilirim. Hücre'ler başlangıçta seçilemez, ama ebeveyn destelerinin havuzuna eklenmiş gibi davranırlar. #tasarlanacak
- Tip Destesi: (Type Bundle) Belirli tip kartların oluşturduğu, başlangıçta seçilemez, alternatif erişim yolları olan destelerdir. Örneğin: Köleler destesi seçilemez. Oyun esnasında bu tip destesinden çekim yapabilen tetikleyicilerle erişilebilir. Bazı tip desteleri sınırsız olabilir. Bu destelerden ne kadar kart çekersen çek, deste adetinden eksilme yaşanmaz.
- Durum Destesi: (Situation Decks) Ölen kartlar ölüler destesine gider. Farklı destelerin masadan ayrılan kartları depoladığı farklı mekanikleri olabilir. Örneğin bir ülke becerileriyle "Yükselmiş" olup "Yükselmişler" destesine ayırılır, sonra özel tetiklemelerle oradan başka bir şekilde değerlendirilebilirler vesaire.

Deste Seçimi:
Oyuncular ilk seçimlerinde istedikleri desteyi seçebilirler. Ancak devamındaki her deste seçimleri ilk destenin bitişiğindeki bir deste olmak zorundadır. Oyuncular bu seçimi yaparken ilk alan son alır prensibini uygular. İlk alan son alır (Choose order: P1, P2, P2, P1): Bir oyuncu ilk deste seçimini yaparsa, deste seçme sırası rakibine geçer. Rakibi iki destesini de seçince, ilk oyuncuya ikinci destesini seçme hakkı geri verilir. Bu ilk seçim yapan oyuncuya aynı zamanda son seçtirerek karşıt bir strateji geliştirme fırsatı verir.

### Anahtar Kelimeler
#### Puana bağlı anahtar kelimeler  
Puan: Karakterin en genel puanıdır.  
Destek: Kartın başlangıç değerinin üzerine yükselmiş puan aralığıdır.  
Can: Kartın 0 ile başlangıç değer arasındaki puan aralığıdır.  
Düşük can: Can aralığının yarı noktasıyla sıfır arasında kalan alandır. (Eğer can ikiye tam bölünmüyorsa aşağı yuvarlanır)  
Üstün: Bir hedefe kıyasla puanca yükseksem.  
Alçak: Bir hedefe kıyasla puanca düşüksem.  
  
#### Grid işaretleri  
Karşım  
Bitişiğim: Kartın dört yönündeki bitişik slotlar.  
Çevrem: Kartın sekiz yönündeki hem bitişik hem çapraz en yakın slotlar.  
İki yanım: Sağ ve soldaki bitişik slotlar.  
Ardışığım: Ön ve arkadaki bitişik slotlar.  
Sağım/solum/önüm/arkam: Tek yön bildirir, en yakın slot.  
Yön + ilk: Bir öncekinin belirttiği yönün üzerine, o yönde en yakından başlayarak menzilsiz tarama yapar ve şarta uyan ilk slotu işaret eder.  
Eşleniğim: Gridin y-axis dizilimindeki ayna görüntüsünde karşıdaki slot.  
Safdaşım: Aynı satır üzerindeki tüm slotlar.  
Sıradaşım: Aynı sıra üzerindeki tüm slotlar.

#### Beceri açıklamaları
Aksiyon: Tüm kart aksiyonlarına denir. Hareket etme, hamle, turluk, pasif, kondisyon tetiklenmesi bunlara dahildir.
Aktif Aksiyon: Oyuncunun komutuyla yaşananlara denir. Örneğin rakip kartımı zorla hareket ettirdiyse o bir aksiyondur ama aktif aksyion değildir.
Pasif: Aktivasyon beklemeden, daima çalışma ve gözlem içerisinde olan, çoğu zaman şartlara bağlı becerilerdir.
Hamle: Kartın özel becerisidir. Her kartta olmaz. Kullanılınca diğer her şeyden öncelikli yaşanır (kurulum sekansı hariç, orada normal şekilde sıraya girer (eğer bir hamle kurulum sekansını henüz başlamamışken tetiklenirse sekanstan önce pat diye etkisi uygulanır, sekansa girilmez)). Hamleler hazır olunca ikonları paralyarak kendini belli eder. Rakip turu esnasında bile kullanılabilirler. Her birinin gerekli Kıvılcım miktarı vardır. Bazı hamleler 2 kıvılcımla çalışırken bazıları 4 kıvılcımla çalışır. Kıvılcım hiç girilmemişse hamle hakikaten tek kullanımlıktır.
Tur Başı: Turun başlangıcında otomatik tetiklenir.
Tur Sonu: Turun sonunda otomatik tetiklenir.
Turluk: Turda bir kere kullanılabilir. Kartın üstünde kocaman indicatör çıkarır kullanılabildiği vakit. Tıklayınca aktive olur ve etkisini uygular. Çoğu zaman "Önüme vururum" veya "En küçsüz safdaşıma destek veririm" gibi tıklandığı an hedefleme olmaksızın yaşanabilen, düz becerilerdir (karmaşık olanları, hedefleme gerektirenleri de var elbet).
Karakteristik: Kartın üzerindeki düz yazı gibi gözükür. Bu aslen bir pasiftir. Kartların karakteristikleri hamle, turluk, becerilerini, etkileşimleri, eklentilerini modifiye edebilir, ekstra efektler ekleyebilir.
Oyna: Bu kart masaya oynanırken gerçekleşen bir beceridir.
Ölüm: Kart ölürken son defa tetiklediği bir beceri.
X Puan: Bir puan eşiğini geçtiğinde tetiklenen beceri.
Aklıma gelmeyenler var hala.
# Oynanış:
## Kazanma Şartları
### Fark koruma
Oyuncuların puanları her tur sonu kontrol edilir. Eğer bir oyuncu tur sonundayken rakibine belirli bir miktar puan farkı oluşturmuşsa, oyun kapanış vaziyetini tetikler. Oyuncunun sonraki turunun sonunda puan farkı hala en az belirlenen miktardaysa, oyunun galibi olur, eğer değilse, kapanış vaziyeti iptal olarak oyun akışına geri döner.
### Tur doldurma
Her modun bir maksimum tur limiti vardır. Bu limite erişilince, o tur oyuncuların puanları arasından hangisi öndeyse o galip sayılır.
### Kitle İnfaz
Bir oyuncunun turunun sonunda, rakibinin masasında konumlanmış bir kart kalmamışsa, oyunu kazanır.
## Oyun Modları
### Classic
Birebir savaş versiyonudur. İki tarafta ikişer deste seçer ve oyuna başlarlar. Her tur 2 kart çeker, 2 kart oynarlar. Rakibe 20 fark atıp bu farkı bir tur boyu koruduklarında veya 10 turu doldurduklarında kazanırlar.
### Battleground Loaded
Oyunun başlangıcına Hazırlık Fazı başlar. Oyuncular 12 kart çeker ve bu kartların 8 ini, 2 şer 2 şer aralarında sıra dönerek masaya konumlandırır. Sekiz kartta yerini alınca veya adımlar pass geçilince Hazırlık Fazı biter, turların doğal akışı başlar ve aksiyon alınabilir olur. Her tur 2 kart çekilir ve 2 kart oynanır. Kazanma şartı Kitle İnfaz ve Tur Doldurma 10'dir.
### Centuries
Üç maçın ikisi veya beş maçın üçü şeklinde kazanılan, art arda maçların oynandığı ve her maç arası destelerin değiştirilebildiği bir oyun modudur. Oyuncular ikişer deste seçerek maçlarına başlarlar. Her maç 20 fark koruma veya 8 tur limiti şartlarına sahiptir. Her rauntun sonunda bir oyuncu galibiyet puanı kazanır. Tekrar deste seçimi yapılır ve oyuncular önceki seçimlerine bitişi yeni bir desteye erişim kazanabilirler. Sonraki rauntlarında o ana kadar seçmiş oldukları tüm destelerden seçim yapabilirler. Desteler raunt aralarında yenilenmez, ölüler ölü kalır ve desteler tükenebilir. Tükenen bir desteden çekim yapılamaz. Her raunt sonrası, oyuncunun masasında kalan kartlar ait oldukları destelere geri döner.
### Hikaye
Hikaye odaklı, kurgulanmış senaryoların yapay zekaya karşı oynandığı moddur. Çeşitli kazanma kondisyonları, tur sayılarına sahip olabilir. #tasarlanacak şimdilik elleme
### Clash
Masanın boyutu 9x7 dir. İlk 3 satır kırmızı takıma, son 3 satırsa mavi takıma aittir. Ortadaki sahipsiz satıra iki taraf tarafından kart oynanamaz. Her bir kartın satranç misali bireysel hareket ve hedefleme biçimlerine sahip oldukları, mekansal konumlanmanın çok daha önemli olduğu bir versiyon. Sıra tabanlı bir moba gibi işlev gösterir neredeyse. Masada rakibin yarısına kart konamasa da yürünerek işgal edilebilir. Masa Battleground Loaded daki gibi önceden hazırlanır ve azalan kart çekme sayılarına sahiptir. #tasarlanacak şimdilik elleme
## Eşleşme Tipleri
### 1v1 PVP
Ana eşleşme biçimi. Tüm oyun modlarını kapsar.
### 4 Player Tournament
Not considered as of now.
Herkes birbiriyle vs atar, her maç neticesinde en çok toplam fark puanla kazanandan sonuncuya doğru sıra olur, sonra en iyi ve en kötü eşleşirler, bu eşleşmenin best of three sine bakılır ama ilk turdaki maçta hesaba katıldığından ilki kazanmış olan direk avantaja sahiptir.

Example of broken matchmaking
a b c d  
1 0 1 0  
2 1 1 0  
3 2 1 0  
  
Tur 1  
a ve b den a  
c ve d den c  
  
Tur 2  
a ve c den a  
b ve d den b  
  
Tur 3  
a ve d den a  
b ve c den b  
  
YA DA  
  
a b c d  
1 0 1 0  
2 1 1 0  
2 2 1 1  
  
Tur 1  
a ve b den a  
c ve d den c  
  
Tur 2  
a ve c den a  
b ve d den b  
  
Tur 3  
a ve d den d  
b ve c den b
### 2v2 PVP
Not considered as of now.
### 1v1v1v1 PVP
Not considered as of now.
### PvE
Considered #tasarlanacak
### PvE Story Mode
Considered #tasarlanacak
# Sistem Tasarımı
## DeckManager çalışması
Destelerden kartlar rastgele çekilir ve her çekimde deste karıştırılır. Çekilen kart seçim havzasına dizilir. Kör seçimde kartların sırtı dönük dururken elemeli seçimde vesaire kartın ne olduğu görülebilir. Oyuncu burada belirli kurallara uyarak al - bırak yapar ve nihayet havzayı çekmeyi seçtiğinde kartlar eline gelir. Standart turlar için seçim tipi kör çekimdir.
  
Çekim Tipleri:  
Kör çekim: X desteden Y kadar kart çek. Oyuncu çekmek istediği desteye tıklar ve bir kart çeker ancak bu kartın ne olduğunu bilmez, kartlar sırt görünümünde tutulur, ancak eline gelince görür.  

Elemeli çekim: X desteden Y kadar kart çek ve Z kadarını geri karıştır. Çektiğin kartlar seçim havzasına ilk olarak arkaları dönük gelirler. Bu haldeyken oyuncu istediği gibi kartları geri karıştırıp tekrar çekebilir. Kartların önünü çeviren buton bulunur. Tıklamasıyla kartlar açığa çıkar ve geri karıştırma serbestliği biter ve aralarından seçim yapmak zorundadır. Beğenmediğin (belirli bir miktar) kartı geri karıştırırsın. Bunun formatı 2/4 yani dört kart çek ikisini ele veya mesela 1/3 yani üç kart çek ikisini ele gibidir. Örnek: Üç kart çek, birini ele. Bu üç karttan birinden vaz geçtiğinde diğer ikisi otomatik eline gelir.
  
Otomatik çekim: Çekim destesi (veya desteleri) zaten otomatik bellidir ve seçim havzası hiç açılmadan kartlar direk oyuncunun eline gelir. Örneğin: Masada "Bir dostu öldürür ve destemden rastgele bir kart çekerim." gibi bir efekt tetiklenince oyun o kartı pat diye çeker.

Oynamaya Çekim: Çekim onaylanınca kart oyuncunun eline gelmek yerine direk masaya oynama sürecine sokulur. Bazı çoklu seçimlerde bu oynama sürecine sokulma art arda gerçekleşir.
  
Seçimli çekim: Oyuncunun karşısına belirli kriterler etrafında kartlar çıkarır. Bu ekranda oyuncunun bir seçim kotası vardır ve o seçimleri yapınca kartlar eline gelir. Örneğin: Bir kartın "Bir Köle seç" becerisinin tetiklenmesiyle üç köle kartı ekrana seçim için gelir. Oyuncu bunlardan birini seçince kart eline gelir. Eğer bu "İki köle seç" olsaydı, oyuncu iki köle seçtiğinde eline gelirdi. Burada aynı tip kartların birden fazla seçilebilmesi default olarak ok olsa da bazı seçim türleri için engellenmiş olabilir (her seçim başka tip kartı zorunlu kılar gibi). Seçimli çekimler özel ayarlara sahiptirler ve Seçimli Çekim Öğesi olarak (SO olarak implemente edilebilir) önceden hazırlanırlar. Yani örneğin üç kölenin çekilebilirliğini ve çeşitli ayarlarını belirten bir öğe olur, bu kartlar o öğeye seslenerek deck manager ı çağırır.  
  
Aramalı Seçim: Belirtilen desteden (bazen erişimdeki tüm destelerden) kartlar taranarak belirli bir tipe, can seviyesine, eklenti sahipliğine vesaire sahip kartların listelendiği özel bir geçici çekim havuzu oluşur ve buradan çekim yapılır. Örneğin: "Destelerden bir yaratık çek." dendiğinde destelerimdeki tüm Yaratık tipine ait kartlar arasından bir seçim yapılır. NOT: Şimdilik yalnızca tipe duyarlı arama yeterli. Bu çekim tipi ya otomatik ya elemeli olabilir, kör olamaz.  
  
Desteye geri karışan bir kart o desteyi shuffle lar. Desteler tükenirse kart çekim listesinde gri olup artık seçilemezler. Destelerin sol üstünde içlerinde kaç kart kaldığı yazar. Oyuncu yalnızca kendi erişimindeki destelerin sayısını görebilir. Çekim paneli oyun sisteminin oyuncunun kart çekmesini istediği zaman otomatik açılır. Destelerin dizildiği bir layout ve seçim havzasının altında yer aldığı bir diğer layout vardır.  
  
İstisnai durumlar bazı destelere geçici erişim sağlayarak onlardan da kart çekmeye izin verir. Örneğin, "Rakibi bir destesine erişirim." diyen bir kart var diyelim. Bu kart aktif olduğu sürece oyuncu o desteye geçici erişim sağlayarak çekim yapabilir, kart çekim panelindeki deste seçenekleri arasında onu görebilir.
  
Vaziyete özel desteler mevcuttur. Bunun en sabit örneği Ölüler Destesi'dir. Şu an başka bir vaziyet destesi tasarlanmasa da, örneğin "Arınmışlar" diye bir deste eklendi ve bu şartın tetiklendiği kartlar ölmek yerine o vaziyet destesine döndüler. Daha sonradan başka bir kartta bu vaziyet destesinden çekim yapmayı mümkün kıldı. Oyunda bu tür vaziyet desteleri var olacaktır.

Esasında MaviOyuncuÖlüler ve KırmızıOyuncuÖlüler desteleri vardır. Ölüler destesi ise bir çatı görevi görerek ikisinden de seçim yapmayı mümkün kılar. Yani bir mavi takım kartının "Ölmüş bir dostumu diriltirim." demesi halinde mavi oyuncu ölüleri çağırılırken, "Ölmüş birini diriltirim." demesi halinde rakibin destesini de kapsayan bir havuzdan çekim yapar.  
  
Destelerin tanımlamalarının saklandığı SO öğeleri okunarak oyun başında onların oyun sürecinde işlenebilir kopayaları olarak davranacak yeni deck instance ları yaratılır. Bir oyun seansı devam ettiği sürece sahne vesaire değişse bile onlar sıfırlanmaz, ancak oyun bitince silinirler ve oyun başlayınca tekrar SO dan yaratılırlar. Bir deste yaratılırken içeriğindeki sade, seçkin ve özel kartların adedi farklı oranlarda yaratılır. Sade kartlardan 3'er tane olur ve normal şekilde çekilip harcanırlar. Seçkin kartlardan 2'şer tane olur ve normal şekilde çekilip harcanırlar. Özel kartlardan 2'şer tane olur ancak kopyalardan biri çekilirse, diğeri yok olur. Bu özel kartın oyundaki adedini arttırmadan denk gelme oranını güçlendirir.
## Oyun modu yaratıcı
SO olarak oyun modları yaratılabilir. Bu öğe yaratıldıktan sonra üzerindeki selectable lar seçilerek, sonra sayılar girilerek mod özelleşir. Daha sonradan bunlar Eşleşme başlatıcı yazılımca kataloglanır ve oyuna girmeden önce oyun modları listesi olarak sunulur. Oradan bir mod öğesini seçersin ve sahen kurulur, gerisini oyun kurucu scriptler halleder. Bu SO'da oyun tipi (classic, centuries, battleground  loaded, clash), bitiş eklentileri (birden fazla olabilir (max tur integer girilir, puan farkı integer ayarlanır, infazda minimum düşman sayısı integer)), gird büyüklüğü x-y, başlangıçta çekilen kart, her tur çekilen kart, her tur oynanan kart, turluk kart hareket hakkı, başlangıçta seçilebilen deste sayısı (ve varsa her maç arasında seçilebilen ekstra deste sayısı)
## Kazanma şartı, puan sayımı ve maç ilerlemesi çalışması
Oyun kendi içindeki durumları gereksinim dahilinde düzenli kontrol eder ve gerekli sistemlere sinyaller gönderir. Oyun modunu GameSceneInitializer bilir ve sahneyi ona göre kurar. GameManager'sa süregelen yoklamalardan sorumludur. Onun yancısı olarak davranan pek çok servis ve class vardır. Yoklamalar ve değerleri ilgili sistemlerce tutulur ve GameManager bir beyin görevi görerek yalnızca sorguda bulunur ve neticesinde gerekli birime iletir gibi.  

Oyuncuya ait işlemler ona özel bir sistemle halledilir. İki oyuncu da kendi managerlarına sahiptir ve bunlar oyuncuların mevut puanları, kartları, el bilgileri ve daha bir sürü akla gelebilecek bilgi, işlem, getter fonksiyonunu falan halleder. Oyuncu skoru masadaki tüm kartların puanlarının sayılmasıyla belirlenir. Her puan güncellemesi eventinde bu değer yeniden sayılarak hem UI'a, hemde ilgili sistemlere işlenir.  

Tur oyuncuya geçince kart seçim ekranı açılır. Kör seçim söz konusuyken, oyuncu istediği destelerden belirtilen miktar kart çeker ve seçiminden mutlu olana kadar geri karıştırabilir, onaylayınca da eline alır, panel kapanır. Ardından elindeki kartları oynayarak ve aksiyonlar alarak tur işlemlerini bir bir takip eder. Oyuncu kart oynamak istemezse tur sayacının üzerindeki "Adımı atla" butonuna basarak kart aksiyon adımına geçiş yapabilir. Burada da aynı şekilde adımı atlarsa da turu sona erer ve tur rakibine geçer. Oyuncu bir adımı atlamaz ve alabileceği aksiyonlarını tüketirse turu otomatik geçer. Eğer adım açıldığı an oyuncunun alabileceği aksiyon yoksa adım otomatik geçer. Her aksyion eventinden sonra adımlık potansiyel hamlelerin listesi kontrol edilerek yapılır bu. Eğer hiçbir adım geçişi olmazsa, bu sefer adım geri sayımı adımı sona erdirir. Turlar içerisindeki adımlara ayırılmış üç tip süre vardır, kart çekme adım süresi, kart oynama adım süresi ve aksiyon adım süresi. Bu süreler adım başladığı an geri sayıma girer, son 15 saniyeleri kaldığında görsel bir zaman tükeniyor gösteriminde bulunur (bir slider tükenmeye başlar) ve zaman tükenince şu şekilde adımı sonlandırır: Eğer kart çekiminde süre aşıldıysa rastgele erişilebilir destelerden otomatik kartlar çeker, eğer kart oynama adımındaydıysa sadece adımı geçer, aynı şekilde aksiyonları da dümdüz atlar.

## El davranışı, inceleme paneli, açıklama metinleri ve tarih kaydı  
Desteden çekilen kartlar oyuncunun eline gelirler. El görünümü açılıp kapanabilen bir alan halindedir. Ekranın kartların topluca durduğu bir görünüm ve üzerinde de açılma çağrısı için bir buton bulunmaktadır. Bu butona tıkanınca el açılarak genişler ve kartlar OnHover kazanır. Kartın üstüne mouse getirilmesiyle kart öne çıkar ve boyut/pozisyon değiştirerek belirginleşir.  
  
Karta tıklanması halinde inceleme paneli açılır. İnceleme panelinde kartın görseli, adı, hikaye açıklaması, aidiyet destesi, tipi, becerileri (turluk hamle aktif özel etkileşim ne varsa burada metinler halinde listelenir), puan gibi temel değerleri (sıfır olanlar gizlenir), ve eklentilerinin listesi vardır. Bu görünümdeki anahatar kelimeler ve kondisyonların üzerine hover yapılınca açıklama popupları belirir. Ayrıca eğer kartın kostüm seçenekleri varsa bir kozmetik seçim menüsü belirir. Burada costüm image lar dizilir ve oyuncu scroll yaparak kaydırır. Selection ın ortasındaki kostüm seçili sayılır. Oyuncunun sahip olmadığı kostümler gri gözükür, sahip olduklarıysa renkli. Oyuncu sahip olmadığı bir kostüm ortaya gelicek şekilde kaydırırsa hiçbir değişiklik olmaz, ancak sahip olduğu bir kostüm ortaya gelirse kartın mevcut sprite görseli bu kostüm görseline çevrilir. İnceleme paneli aslen bir künye görevindedir ve işevsel bir anlam barındırmaz. İnceleme paneli, masadaki kartlar için de erişilebilirdir.  
  
Eğer elde bulunan karta tıklanmak yerine sürükleyip bir mesafeye bırakılırsa kart masaya oynanma işlemine sokulur. Oynanma sürecinde, eğer kart tipi sıradan bir birim kartıysa griddeki uygun slotlar parlar ve konumlama grid tarafından halledilir. Eğer kartın bir OnPlay becerisi var ve bir hedeflemeye ihtiyaç duyuyorsa, oyuncu önce onun hedeflemesini yapar, ardından oyun konumlandırılacak grid seçmesini istiyorsa konum seçmeye devam eder. (Önemli fark, bazı kartlar yalnızca OnPlay tetikleyip yok olabilir, ya da direk OnPlay becerileriyle hedefledikleri slota inmeye zorlanabilirler). Eğer kart bir Event veya Dream vesaireyse zaten masada konumlanmaz. Augment tipiyse de yapışabileceği kartları gösteren grid parlaması yine grid tarafından handlelanır.
  
Oyuncular birbirlerinin ellerini istisnai çağrılar haricinde göremez. Rakibin eli daima kartlarının deste arka görselleriyle gözükür ve üstlerine tıklanamaz.  
  
Oyunun menüleri, özellikle inceleme panelleri ve açıklama menülerinde anahtar kelimelere ait cümleler üstüne işaretçi getirilmesi halinde o kavramı açıklayan küçük popupların o konumdan yükselmesine sebep olur. Oyuncu işaretçiyi açıklaması yapılan kelimenin veya ikonun üzerinden çekince popuplar kapanır. Bunun için bir sözlük halinde anahtar kelimeler ve ikonların tekabül ettiği açıklamaların cataloğunun tutulduğu bir SO vardır. Metinlerin yalnızca o anahtar kelimesi hover halinde tepki verir.
  
Oyun içerindeki her aksiyon ve adım bir oyun takipçisi yazılımı tarafından sürekli dinlenmektedir. Bu yazılım her can değişimini (fail, özne, değişim miktarı), kart aksiyon veya hamle tetiklenmesini (pasifler ve eklenti tetiklemeleri kaydedilmez ancak değişim miktarında onların etkileri de kaydedilir, yani bir saldırı yaptım ve pasiflerim eklentilerim tetiklendi neticede 5 vurmuş oldum, oyun o 5 vurduğumu (değişimi) kaydedicek, faili ve hedefi kaydedicek o kadar), adım ve geçişini, oynanan kartı, ölen, desteye veya ele geri dönen kartları girdiler halinde bir tarih dizinine işler. Bu tarih dizini metin girdileri halinde kaydırılabilir bir panel görünümünde her yeni aksiyonun başa eklenmesiyle oyun içi gözükebilir.
  
Kostüm sistemi, oyuncuların kozmetik ürün sahipliğini barındırır ve bu sahipliğe göre inceleme menüsünde seçilebilir kılar. Sahip olunan kostüm id leri bir liste halinde (şimdilik) bir json a kaydedilir ve bu oyuncudan oyuncuya değişir. (şimdilik) bir SkinReceiver scripti hazırla. Bu script oyun içi input text kısmından yazı yazılarak girdi alır, onları json halinde kaydeder ve gelecekte kullanıcı id ye sahip mi diye kontrol eder. Localde tutulur ve kostüm elde etmek için id koduna sahip olup elle girmek gerekmektedir. Bunun menüsüde ana menüden erişilir.
## Masa çalışması  
Masa gridi bir yazılımla takip edilir. Bu griddeki her slotta ne kart var, ne durumda, kime ait bunun takibini o yapar, bir listede tutarak istediği an erişebilir. Bu masa denetleyicisi masadaki hedeflemeleri hesaplar ve hareketleri gerçekleştirir.  
  
Kartların spesifik hedefleme erişimleri vardır. Örneğin bir kart hemen önündeki üç slotu hedefler. Başka bir kart rakip arka safta karşısındaki kişiyi hedefler. Örneğin bir kart en düşük canlı rakibi veya dostu hedefleyebilir. Bu sistem bir kartın aksiyon veya hamlesinin butonu üzerine hover yapılması durumunda o aksiyon kimleri hedef alacak işaretler. Geleceği göremez ve işaretlerinde yalnızca mevcut durumla ilgilenir. Karşı üç rakibi hefefleyen aksiyon o üç slotun parlamasıyla gösterilir, en düşün canlı dostu hedef alan kartsa aksiyon hover durumunda o dostu görsel olarak işaretler. Kartlar kendi animayonlarını lokal idare ettiğinden onlara hadi parla diye çağrı yapar. Aksiyon onanırsa, faili ve hedefi alıp aksiyon manager a iletir. Aksyion manager onu devamında tekrar sorguya çekebilir. Örneğin hamlenin neticesinde ölen bir düşman oldu ve çevresindeki kartlar hasar alacaksa, bu kartların kimler olduğu otomatik olarak grid managera sorulur ve anında hesaplanıp geri dönüş alınır. Manager binbir çeşit konumda ve vaziyetsel parametreyi gözden geçirerek işarette bulunabilir, ancak günün sonunda yalnızca "Burada bu kişi var" demekten öte bir veri işlemez. Mesela konum sorgusunun ötesinde, can seviyeleri, etki sahipliği veya geçmiş etiketi sorgulaması söz konusuysa bu sorguyu o yapmaz, ancak bu sorgunun yapıldığı sistemlerden ona "Şu kartın olduğu slotu parlat" denince onun parlamasını gerçekleştirir. (grid manager hazır masadaki tüm kartların registery sini tutarken ona sorgulatmak ya da en azından aracı olmasını sağlamak çok tatlı olurdu aslında)
  
Eldeki bir kart sürükle bırak yaparak boş bir slota oynanabilir. Kart hoverlandığı gridi aydınlatır ve  yakındaki gride snapler. Eğer dolu bir yere oynanmaya çalışılıyorsa, o dolu slottaki kartı çevresindeki boş bir slota iterek yerine geçebilir. Bu itim esnasında boşluk kayma öncelik sırası daima sırasıyla sağ, sol, ön, arka şeklindedir. Eğer yerine oynamaya çalıştığın kartın dört bir yanı doluysa o nokta oynanabilir şekilde parlamaz ve kart o gride snaplemez. Kartlar oynandıktan sonra hareket aksiyonu kullanarak hareket edebilir. Karta tıklama yapılıp, basılı tutularak sürükleme yapılınca kart hareket ettirilebileceği tüm uygun slotları aydınlatır. Dolu bir slota oynanmaya çalışması durumunda o slottaki kartla yer değiştirirler. Bir kart tipik olarak sadece ileri geri sol olmak üzere dört yöne geçiş yapabilir, çapraza veya ikişer birimlik ilerleme yapamaz. Kartın sürüklenemsinin ardından eğer mevcut gridine geri bırakılırsa, hareket girişimi iptal olur, vaz geçildi gibi sayılır. Aynısı elden sürüklenen kartlar için geçerlidir. Bir kart sürüklenmeye başladığı an yerleşebileceği slotlar aydınlanıp snaplenebilir olur.
  
Kartların hareket aksiyonunun temel kuralları:  
Her oyuncu, turda bir kere istediği kartı bir kere hareket ettirebilir. Bir kartı hareket ettirince, bu turluk hakkı sona erer.  
Hızlı eklentisine sahip kartlar, turluk hareket aksiyonundan bağımsız şekilde, onu harcamadan turluk bir defa hareket edebilirler. Bu hak Hızlı eklentisi adedince artar.  
Yavaş eklentisi o kartın hareket ettirilmesini imkansız kılar.  
Işınlan eklentisi kartın normal hareketinin erişimini evrilterek kart oynanıyormuş gibi bırakım yapılmasını, dost slotlara serbestçe erişip istediği noktaya ışınlanabilmesini sağlar (elden bırakmanın kurallarına tabi olur)  
Geçici Adım, çeşitli tetiklemeler tarafından sağlanır, bir defa beleşe hareket eder.  
  
Bazı kartlar aksiyonlarıyla bazı başka kartların standart bir hareket talebi dışarısında kaydırılmasını talep edebilir. Örneğin: "Vurduğum düşmanı ayrıca arka safa atarım" diyen bir kart. Bu tür hareket hamlesi dışı yer değiştirme taleplerinde, gidilecek yer doluysa şöyle bir ekstra kaydırma veya yer değiş tokuşu gibi politikalar uygulanmaz. Eğer o itilmeye çalışılan yer doluysa, basitçe çağrı geçersiz kalır. Örneğin: "Rakip ön saftaki herkes arka safa kayar, kayamayanlar 2 tur sersemler." dien bir kart tetiklendiğinde tüm bu kartlar arkasını kontrol eder ve yalnızca boş olanlar geçer. Birinin arkasındaki kart yana kaymak suretiyle yer açabiliyor olsa bile bu sorgulanmaz.

Grid kurulumu: Oyun modu yaratımında grid AxB diye bir boyut girdisi yapılır ve grid kendi matrixini o boyuta göre belirler. Daima satırların ilk yarısı kırmızı oyuncuya, son yarısı mavi oyuncuya aittir. Eğer satırlar tek sayıysa, ortanca satır GRİ ALAN olarak tanımlanır ve kalan slotlar kırmızı maviye aynı şekilde ayırılır. Gri alana iki tarafta kart oynayamaz.

Oyun moduna bağlı olarak kartların rakip yarıya hareketi onanır veya engellenir. Classic mod'da buna izin verilmez. Clash modunda buna izin verilir.

SONRASI İÇİN (Takıma dayalı konumlanma sınırlarını aşarak girdin rakipten kala kısmına konumlanabilen kartlar vardır. Gri alana da bırakbilen kartlar vardır.)
## Kart ve deste işleyişi  
Kart öğeleri SO definition ları olarak tutulur ve deste SO larına dizilerek adet ve sıra düzenlemeleriyle barındırılırlar. Bir kart SO'sunun içerisinde: Kart başlık ismi, kart davranışı (unit, event, augment, dream, hazard), kart speciality (standard, elite, special), kart can, kıvılcım değerleri, kart type (catalogue dropbar, aynı anda birden fazla tip olabilir bir kartta, insan, yaratık, hayvan vesaire), kart becerileri (burası aksiyon sistemiye çok alakalı, ancak basitçe bir turluk, tetiklenme, pasif karakteristik, hamle tanımlanabilir, yine selectable şeklinde kataloğa erişilir, aksiyonların içine dair bir data tutmaz kart sadece bir command id ile sinyal yollamayı bilir ve aksiyon sistemi gerisini halleder), kart eklenti listesi (bir selectable ile katalogdan yeni eklenti eklenebilir ve değerleri özelleştirilebilir, örneğin vurma halinde 3 tur kanatacak bir kanama etkisi için selctable dropbar - kanama - tur süresi 5 yapılınca süresi değişir  falan gibi parametrelerle eklentilere özel özelleştirmeler yapılabilir), lore text, id ve görsel eşleri tutan bir kostümler listesi, deckIndex (ait olduğu destenin indexine refernas girilir) ve son olarak cardBackSprite (gizlilik görünümünde kartın mevcut görseli yerine bu geçer, deck manager desteleri sentezlerken her kart öğesinin bu slotuna deckCardBackSprite'ı verir, bu selectable olmasına gerek yok). Bunlar kartın temel karakterini oluştrur ve bazıları maç esnasında değişebilirken (can ve beceri aktivasyonu vesaire gibi), bazıları değişemez (kostüm listesi, lore metni, başlangıçta tanımlı eklentiler gibi).  
  
Kart öğelerinin üç durumu vardır.  
İlki destededir ki bu SO dan kopyalanarak yaratılmış aksiyonsuz bir liste girdisinden ibarettir. Çekilerek ele alınır. İkinci aşamada elde beklemektedir. İnceleme butonuna sahiptir ve oynanmadan önce açıklamada bulunabilecek öğeler taşır. Eklentilerinin bir liste halinde göğsüne sıralar, tip ve isim yazılarını ve kartın puanını gösterir. Üçüncü form masaya oynanınca ortaya çıkar. Bu formda tur mekanizmasına entegredir, savaşır, tipine bağlı aksiyon alır. Kart görünümü eldekinden farklıdır. Bu sefer hamlesnin kullanılabilirliği, tuluğunun kullanılabilirliği, kıvılcım sayacı, can miktarının renk ayarlaması gibi layout değişikliklerine sahiptir. Karın üzerine üç saniye on hover on hover da kart biraz büyüyüp belirginleştiğinde beceri yazıları açığa çıkar. Masadaki kart çağrıda bulununca kendi animasyonlarını üzerinde bulundurup aktive ederken, partiküller bir partikül sistemi araclığıyla, aksiyon sisteminin kararıyla kart üzerinde yaratılır ve oynatılır. Hamle'nin kullanılabilirliği kartın puan değerinin arkasındaki renkte gözükür. Bu puana tıklanmasıyla Hamle aktivasyonu yaşanır ve beceri tetiklenir, hedefleme veya seçim gerektiriyorsa bu işlemler için aksiyon sistemi gerekli diğer sistemleri çağırır. Kart turlukları kartın çoğunu kaplayan bir tıklanabilir ve işaret göstergesiyle belli edilir. Onlar da aynı şekilde tıklanınca gerisini aksiyon sistemi otomatik gerçekleştirir ya da gerekli çağrıları yapar.
  
Etiketler kartın üzerindeki tarihin takibini tutar. Kartın geçmişine yazılmasını oyunun kayıt sistemi yapar. Format: Fail, hedef, etki, etkiId, zaman, şeklindedir. En önemlisi etkiId dir. Mesela bir kart "Bir dostum önceki tur hasar almışsa" gibi bir sorguda bulunacaksa o kartın taglerine, hasar almaya denk gelen id li kayıtlarına ve geçen tur almışmı ona bakılır. Kısacası kartlar bu etiketlerle tarihçelerini üstlerinde barındırırlar. Bazı etiketler, öldürdüm, oynandım, vurdum, hamle yaptım, iyileştirdim, iyileştim, kanadım, hareket ettim gibi bir envai çeşit id ye sahip olabilir. Kart ele geri dönerse bu tarihi kaybetmez ama desteye geri dönerde tarihi sıfırlanır.  
  
Destelerinde SO ları vardır. Burada künye olarak barındırdıkları bilgiler şunlardır: Deste ismi, Deste arka görünümü, Deste ikonu, Deste indexi, desteye tanımlı kartlar listesi, her bir erişilebilir komşu destenin indexini barındıran bir komşu desteler listesi. Bu bilgiler deck manager tarafından ve gerekirse action system vesaire tarafından sorgulanabilir. Hatta bunun için özel bir deste sorgulama scripti olsun, deck managerda çekim yaparken falan onu çağırıyo olsun.
## Aksiyon Sistemi
The stack/queue as the backbone, event-driven trigger detection layered on top, and a middleware-style pipeline for condition interception — with everything defined as composable data rather than one-class-per-card. Unique command creation freedom with (maybe) inherit-overwrite classes. Highly selectable/configurable command creation process (enum polymorphism).

Oyun bir olay-sıra sistemi kullanır. Fifo şeklinde. Tur esnasında oyuncu Hamle kullanabilir veya istediği gibi kart oynayaiblir. Bu aksyionlar alındıkları gibi yaşanır ve çözümlenirler. Ancak eğer Turluk veya Haraket aksyionları denenirse oyun Kurulum Sekansı'nı başlatır. Bu sekansta aksiyonlar çözümlenmek yerine bir yaşanacaklar listesine sıralanmaya başlarlar. Her kartın yapacağı aksiyon ufak bir efektle belli edilir ve aksiyonlar art arda dizilerek resmen bir koreografi kurulur. Bu esnada kart oynanamaz ancak hamle alınabilir. Hamlelerde diğer aksiyonlar gibi sıraya girer. Nihayet oyuncu Kurulumu Tamamla butonuna basınca (ya da adım süresi dolunca) kurulumunu kesinleştirmiş olur. Adım rakibine geçer ve rakibine Hamle kullanma izni verilir. Rakibin kullandığı hamleler anında yaşanır ve kurulumun aksiyonlarını bozabilir (örneğin önündeki rakibe vuracağı kararlaştırılmış bir kartın sonradan Hamle müdahalesiyle arkaya atılarak menzil dışı bırakılması). Rakipte adımını tamamladığında, kurulum uygulanmaya başlar. Aksiyonlar sırayla, bir bir uygulanır. Müdahaleler yüzünden artık mümkün olmayan aksiyonlar doğal olarak tetiklenemez. Liste en sona varınca görünüm son bulur. Bu turda bir kere kullanılabilir ve bu esnada turluk aksiyonların değerlendirilmemesi sonucu tekrardan Kurulum Sekansı'na giriş yapılamaz. 

Ayrıca oyun özel bir Kurulum Çözüm Görünümüne sahiptir. Bu bir göz ikonu şeklinde ekranın kenarında bulunur ve kurulum sekansında ortaya çıkar. İmleç üzerine getirilince sahne değişerek o ana kadar yapılan seçimlerin uygulandığı bir masanın nihayetinde nasıl gözükeceğini gösterir. (mimarisi veya sistemi nasıl olur hiçbir fikrim yok, ancak aklıma gelen en kolay çözüm sahnenin arkasında masanın görünmez bir klonunu tutmak ve mouse gözün üstüne gelince hemen o alternatif sahnede bütün aksiyonları tetikleyip (animasyon tetiklemeleri falan full es geçilir o yüzden salisede sadece sonuç sentezlenmiş olur) görünür kılar. Bunun için GhostActionSystem gibi bir paralel yapı olur, hatta mesela zincirleme olaylar esnasında kart çekme gerektiren aksiyonları bile çözümletir ama bunların hiçbiri gerçek sahneye etkide bulunamaz). Senin tasarım bilgeliğine güveniyorum bu konuda Claude cuğum.

Öncelik belirleme: 
Her kart becerisinin, pasifinin veya eklenti tetiklenmelerinin bile bir priority sayısı vardır. Bu priority sayısında 1'e en yakınlar ilk ele alınır. Her command ayrıca bir overriten priority sayısına sahiptir. Örneğin tipik oalarak bir eklentinin tetiklenişi prio 5 se, bu spesifik kartın üstündeyken değişerek 2 ye iner. Bu prio işlem sırasına aynı anada girilmeye çalışıldığında gözetilir.

Aksiyon kontrolleri:
Bir kart aksiyonunun onanması veya koşulunun tetiklenmesi için birden çok şartın yerine getirilmesini gerektirebilir. Bunlar konuma bağlı olabilir (önümdeki düşmana vururum, arka saftaki düşmana vururum, etrafımdaki 8 kareye vururum gibi), hedefin niteliklerine bağlı olabilir (canı X ten düşük düşman, kart tipi şu olan düşman, bu tur bir dostu öldürmüş düşman), veya daha genel oyun durumlarına bağlı kontroller gerektirebilir (puanda öndeysek, kart adedince üstünsek, masada X miktar eklenti bulunuyorsa). 

Eklenti problemi:
Eklentiler bir aksiyon alınmadan o aksiyonun hedeflemesini, gerçekleniş şeklini modifiye edebildiğinden bu onanma kontrollerinin de önceden ona göre hesap edilmesi gerek.

Kart becerileri  
Beceriler yaratılırken o becerinin nasıl aktive olduğu bu çağrılarla yapılır. Örneğin bir kart masaya oynandığında (OnPlay) etrafındaki dostları iyileştirecekse bunun için özel komutu "OnPlay" fonksiyonu overritelanarak yazılır.
  
Aktif Aksiyonlar:  
OnMove, kartın hareket etmesiyle yapılan aksiyon çağrısı.  
OnTurnAction, kartın turluk becerisinin kullanılması.  
OnActiveAbilitly, aktif becerinin kullanılması ve tüketilmesi.  
  
Tetiklemeler:  
OnTurnStart, tur başında tetiklenir  
OnTurnEnd, tur sonunda tetiklenir  
OnPoint, kart bir puan miktarına sahipse  
OnPointReached, kart bir puan miktarı veya fazlasına sahipse  
OnPointDown, kart bir puan miktarı veya azına sahipse  
OnDraw, kart ele çekim esnasında tetiklenir  
OnPlay, kart masaya oynanırken tetiklenir
OnOtherPlay, masaya başka bir kart oynandığında tetiklenir
OnDeath, ölünce tetiklenir
OnHit, saldırı onanınca tetiklenir  
OnGettingHit, saldırı alınca yaşanan tetiklenme  
OnHeal, can yenilenmesi üzerine.  
OnSupport, candan fazla puan değeri kazanma.  
OnCondition, bunun çok çeşidi olur, özellikle tetikleme eklentileri hep özel çağrılara sahip olacak  
On anything really, unuttuğum bir sürü tetiklenme şartı var. Bunlar kolayca eklenip, her birine özelleşmiş komutlar ve beceri zincirleri yazılabilmeli, iterasyonu ve inovasyonu kolay olmalı.

## Multiplayer işleyişi  
Görünüm farkları oyunculara özeldir. Örneğin rakibin elindeki kartlar sırt görünümlerini takınır, on hover tetikleyemez ve tıklanamazlar. Rakibin masasındaki Gizli etiketine sahip kartlar masada slotlarda görünmez haldedir. Rakibin turundayken adımı pass geçme tuşuna tıklanamaz. Rakip kart öğeleri butonlarının hiçbirini aktive etmezler. Rakibin masadaki kartlarına tıklayınca inceleme menüsü açılabilir.  
  
Deste manager yerel işlem yapıp sonucu multiplayer olarak paylaşır. Bunun sebebi, ben bir kart çekmek için ekran açıp kart çekerken, bunların görsel aktivasyonlarının rakibin oyun öznesinde de tekrarlanmamasıdır. Yalnızca kartların çekimi onandığında rakipte de bu gerçekleşir ve kartların ele geçişini görebilirler.

## Partikül ve animasyon çalışması.  
Partikül sistemi çağırılır ve istenen noktaya, katalogdan bir prefab çağırır. Partikül cataloğu partikül çağıracak nesnelere girilerek selectable olarak sunulur. Örneğin Kanama eklentisine OnHit anında +Particle effect ekliyorsun, burada katalogdan effect select leyip sonra offset belirliyorsun ve partikül çağrısını aksiyonun içine entegre etmiş oluyorsun. Partiküllerin id leri önemli zaten. Kanama birine vurunca vurduğu kişiyi, offseti ve partikül id sini veriyor, partikül sistemi de hedef noktada, offset ekleyip partikülü tetikliyor. Animasyon sistemide bu selectable ve id ileterek oynattırma olayını işliyor ama tabi burada offset yok ve animasyonlar kartın üzerindeki animatörde tutuluyor, kart öğesi animasyon sistemi tarafından hedef olarak alınıp o animasyon id sine göre animasyon tetikliyor. Kart ve aksiyon etkileşimleri dışındaki animasyon ve partiküller, daha az generalized tanımlamalarla yine particule ve animation managerlar tarafından yönetilir. Mesela oyunu kazanan takıma bağlı aktive olan partikül yağma efekti vardır ve bunun çağrısı gelince uygular.  
## Menü, oyuncu ayarları, oyun kurma ve profil  
Profile girince oyuncu kendine bir profil görseli ve kullanıcı ismi belirleyebilir. Profil görseli değiştirmeye çalışınca bir panel açılıp bir dizi hazır görsel arasından seçim yapılır. Kullanıcı adıysa 16 karakteri geçmeyecek şekilde belirlenebilir.  
  
Profilde oyuncunun istatistikleri ve ilerleme seviyesi gözükür. Oyuncunun maç tamamlaması durumunda kayıt sistemi onun kullandığı desteleri +1 ler. Bu ekran tümüyle entegre edilmeyecek, yalnızca bu playerpref read iyle oyuncunun favori destelerin arkası gösterilerek "En sevdiğin desteler" diye bir sıralama yapılacak ve oynanma sayısı verilecek.  
  
Oyna deyince oyuncu eşleşmesiyle alakalı seçenekler çıkar, TEST, PVP, PVE, Hikaye şeklinde. PvE ve Hikaye seçenekleri şimdilik tıkalnamaz olacak implemente de edilmeyecek. Test seçilince oyun modu (classic, centuries, battleground loaded etc.) seçmemiz istenir ve seçim tamamlanınca oyun başlar. PVP seçeneği ise bize iki seçenek verir, oyun kur, oyuna katıl. Oyuna katıl butonunun altında da bir yazı girme kısmı vardır, oraya host ip gireriz ve LAN üzerinde bu oda mevcutsa odaya katılır. Odaya katılınca hostun oyun ayarları gözükür ama şimdilik sadece Oyun Modu gözükceketir bir text halinde. Oyun kurmaya tıklayınca karşımıza yine bu ayarlar arasından selectable seçim yaptığımız bir panelle karşılaşırız. Oyun modu, oyun modları kataloğunun selectable kısmından seçilir belirlenir. Oyun kurucu, odasına katılan kişinin kullanıcı adı ve ip sini görür. Bu ismin yanında bir de hazırlık ikonu vardır. Bu ekranda kurucu için de katılımcı için de LEAVE ve READY butonları vardır. Leave odayı terk ettirir, eğer kurucu terk etmişse katılımcı da otomatik terk eder. İki oyuncu da Ready verince oyun otomatik başlar. Kimin kırmızı kimin mavi taraf olacağı rastgele belirlenir.  
  
Ayarlarda menüsünde yalnızca ses seviyesi ayarı vardır.  
  
Çıkış oyunun kapanmasına sebep olur.  
  
## Eşleşme işleyişi:  
  
Test oyununda oyuncu tek başına maça girer. Oyun normal maç kurulumunu yapmak yerine masada önceden kurulmuş öğelerin bulunduğu bir Test Scene i açar. Oyuncu kendi turuyla serbestçe hareket edip oyunu oynayabilir. Rakibin turlarıysa anında pass geçildi çağrısı yapar (kart çekmeyi engelleyen bir mantığa gerek yok, rakibin elinde yığılıp gidebilir o kartlar). Kısacası rakibin sonsuza dek pass bastığı ve aslen olmadığı bir alanda oyun testi yapılabilir.

Normal bir maç yüklemesinde önce deste seçim ekranı gelir. Bu alanda oyuncular sırayla destelerini seçerler ve son destenin seçilmesiyle oyun sahnesi kurulur. Gerekli sistem davranışları gerçekleşir, açılış kartları çekilir ve turlar akmaya başlar. Maçın sonunda oyun sonuç ekranını çağırır ve kimin kaç farkla kazandığı, en çok hangi kartı kullandığı, bir turda en yüksek hasarı kim çıkardı gibi statlar kayıt sisteminin girdileri elden geçirilerek gözükür. Eğer oyun çok maçlı bir yapıdaysa (centuries oyun modu gibi) oyun tekrar deste seçim ekranına döner ve tekrar oyunu kurar ve tekrar ve tekrar ve yine aynı sonuç ekranına ulaşana kadar.  
  
Oyun sahnesi yüklense ve kurulsa da görsel açılışı henüz gerçekleşmez. Oyuncuların deste panelinden seçimlerini yapmasıyla bu panel kapanır ve oyun masası açılır. Açılırken bir sahne açılış animasyonuyla giriş yapılır. Bu bir timeline öğesi olarak güzel bir giriş efekti sağlar.

# Gözden geçirelecekler

Turluk 3 karta çıkar, cidden, başlangıçta falan 2 kart oynanınca ne oluyor tam olarak knk?

Can sıkışması, dört canların birazını 3'e çek, 5lerin bazısını 4 e çek, oyunda savunman yoksa düşmen gerek

Formasyon teorisi, oyun döngüsüne uygun kartlar tasarla

Bileşen kur, Ofense, Savunma, Destek
Savunma noktalarımda zayıflıklar olmalı ve bunlar bazı kanatları korumalı, bunun ötesinden bazı etkilerle saldırılar gerçekleşebilmeli, eğer basınç noktasını kaybedersem savunmam çöker

Hatların düşüşü, kriz yönetimi, düşen yerde yeni kanat kurup savunmaya devam etme

Hattını düşürünce zincirleme kıyım fırsatları, düşman öldürdükçe, canları düşürdükçe tetiklenen yetenekler, saklanan hamleler

Tekrar formasyon alış, açıkça güçlü düşmana karşı alan etkili antisnowball yaklaşımlar

Ezme ve kombo tetikleme, geri düşen düşmanla arayı iyice açmak için elinden geleni yap. Ardından bir kroşendo ile oyunu bitir

OYUN KROŞENDOLAR İLE BİTMELİ, acı verici yavaş sonlarla değil, satranç bile bir an fark ediyorsun ki çoktan snowball olmuş ve tık tık kaybediyorsun sonra iki hamlede

## Binalar
Patton -
Hasar ve iyileştimelere +1 buff
+1 kart oynama kapasitesi

Karga akademi -
Dört kartı iyileştiririm
Dört kart, vuruşlarıyla rakibin son kondisyonunu kırar

Çoban -
Korku dağıt
Üstünsem 2 kat vururum
Büyük elruna faction(Hiddet dağıt, destek kır, rite for the end elruna çağır) 

Gece -
+1 yaratık çek her desteden
Dörtlüdeki dost ölünce, Bir Ceset olarak geri dirilir

Sintra
Önümdeki kartlar ışınlan alır
Aldharon dost ilk kez ölmek yerine, masadaki en güçlü dosta 2 vurarak +2 alır
Patton tersane, önümdeki bir yuvaya kart oynanırsa, o yuvadaki kart elime döner
Doğa, dörtlüdeki dostlar 
Karga, vurulan rakibin kondisyonu kırılır
Çoban: Dörtlükteki dostlar ölmeden önce bir daha Turluk kullanır


Hamle kartlarını arttır
Menzilli kartlar ekle en az 2 tane

# Fikir örnekleri

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