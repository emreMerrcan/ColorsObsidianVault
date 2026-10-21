# Combat Prototip

Dövüş sistemini tasarla ve sade bir sahne oluştur.
- [x] Gün 1: Biçerin sallamalı ve karşıya olan hamlesini kodla. Dash ile olan komboyu ve cooldown u implemente et. Can azalınca dash kısıtlamasının azalmasını ekle. Son olarakta block olayını ekle.
- [x] Gün 2: Düşman ekle. Oyununcunun üstüne gelerek saldırsınlar, dümdüz. Can barları olsun ve hasar alınca sersemlesinler, block ile geri itilebilsinler. Can seviyeleri renkle belli olsun ve bir düşman manager yazılımı spawnratelerini belirleyerek dört bir yandan düşman instantiate etsin endless mode gibi.
- [x] Gün 3: Düşman pathfindingi oluştur ve düşmanların birbirine veya engellere takılmadan ilerlemesini sağla. Oyuncuya kombo sayacı (isabetli vuruş sayacı ekle, tek bir saldırı birden fazla düşmana mükemmel vurursa o kadar artıyor. Bir saldırı yapılırda biri hasar almazda sayaç sıfırlanıyor) Ayrıca dashi inputa bağlı kıl yöne değil, bir saldırı yapılırken geriye dash atmaya çalışıyorum ve dümdüz öne atlıyo çar yön değişemediği için. Screenshake ve screenfreeze ekle.
- [x] Gün 4: Block'u yönlü kıl ve 360 derece pushback yeteneğini ekle. Kılıççı, mızrakçı düşmanları tamamıyla kur. Parry ve dash invincibility ekle. Parry combo sayacına sayılıyor.
- [ ] Gün 5: 
- [x] Ağır atak dash ve soulsurge esnasında tekrarlanmaya çalışılırsa tekrarlanır ve dashi de sıfırlar. 
- [x] Can azalınca soulsurge e girilmez. Soulsurge taban bir değerin üstüne vurulan her düşman başına +2 saniye süre kazanır. Bunun yerine her ek düşmana vurduğunda biraz can çekersin. 
- [x] Orta saldırılar tekrarlanırkenki boşlukta karaktere yön belirletebilirsin ve karakter o yöne bir adım atarak savurmaya devam eder. 
- [ ] Geri itilen düşmanın çarptığı düşmanlara vurup geri itmesini sağlayan sistemi geliştir. 
- [x] HordeBrain'i geliştir ve tüm düşmanları ona bağla, saldırı izinleri ondan gelsin, bir tansiyonmetre oyuncunun üstündeki yoğunluğu ve saldırı çağrılarını yapan bir sayı zamanla artıyor, oyuncu hasar alırsa iniyor. difficultyLevel oyuncunun overall performansını takip ederek ekleme yapıyor tansionmetreye, dövüş boyu oyuncunun girdiği haller takip edilerek oyunun zorlaşması veya kolaylaşması yönünde seviye değişiyor.
- [x] Minyon
- [x] Okçu
- [ ] Atılgan
- [ ] Kalkanlı
- [ ] Bölünen(lav tazısı) büyük düşman tiplerini ekle. 
- [ ] Slow the game down and add long windups and recoveries between all actions.

Nope: Görünmez düşman mekaniğini ve vizyon becerisini ekle. Oyuncunun boşluk yakalayarak görüş elde etme zorunluluğu olsun ve düşman canları sadece bu moddayken gözüksün.

Bu geliştirme demosunun durduğu nokta. Şimdi sanat üretimi, hikaye tasarımı vs. yapılacak ve azar azarda combat sistemi üzerinde deneyler yürütülecek. Sladırı tipleri veya bazı temel mekanikler kökten değişebilir her dakika. Bu demonun amacı bu. Çabuk çakılması.
Devam iki gün deneyler, eklemeler ve düşünceler elde edilecek. Alternatif fikirler ve düşman çeşitleri düşünülebilir. 

Notes: 
Oyuncu daima oyuınun kalbinde durmalı ve çembersel hareketlere odaklandığından kamera ona kitlenmeli.
Spawner koduna dialogdan veya diğer yerlerden çağrı yapılabilmeli. Spawn çağrıları HordeSO lar spawnera iletilerek yapılmalı. Bu iletimden sonra, belirtilen dalgaları, belirtilen süre farklarıyla hayata geçirmek Spawnerın işi.

---
# Aşama 1: Köy Bölümü

- [x] Kullanılabilecek bir sürü asset indir, yer tutucu sanat öğeleri.
- [x] Bölümün şemasını çıkaracak şekilde hepsini yerleştir ve Polygon Collider ekle.
- [x] Sahne metinlerini entegre et ve tetikleme alanlarının ve etkileşilebilirlerin mantığını kodla.
- [x] Timeline ve sekans araştırmasını yap ve kodları birbirine bağlamadan önce sinematik modelini anla (henüz uygulama).
- [x] DialogueManager ve InteractableTrigger düzenlemesi ve EnemySpawner'a yaptığı çağrılar.
- [x] EnemySpawner'ı uygun düşmanları çağıracak şekilde oluştur ve ekle.
- [ ] Player'a yürüme ve dövüşü kısıtlayan iki boolu ekle.
- [ ] Yılan düşman tipini ekle.
- [ ] Kurt düşman tipini ekle. (kurt yerine maymunumsu, kıllı, atılgan yaratıklar olabilir btw, babun gibi)
- [ ] Hayalet düşman tipini ekle.
- [ ] Bulmaca kodunu yaz.
- [ ] Yürünemez ama dashlenebilir boşluk elementi, düşman collider sorunsalına çözüm, interaksiyona girince seni kapıdan geçirip öbür uzaya çıkaran kapı mantığı.
- [ ] Takip eden dost, streeing kullanan, menzil bloğu var bir menzile girince yerinde sabit kalıyor.

# Gelecek Aşamalar:
- [ ] Dost düşman birlikler mantığı. Düşmanlar yalnızca oyuncuya değil, başka dostlara da kilitlenebiliyorlar, en yakın olana saldırıyorlar. Dost birliklerse birebir düşman AI'ına sahip oldukları halde label'ları farklı ve bu yüzden onlara saldırıyorlar. HordeBrain sahnedeki dost miktarına göre düşmanlara ekstra Budget artışı sağlıyor.
- [ ] 
Endeksli düşmanlar


Timeline Guide:
https://youtu.be/mpRnKI8amEc
https://youtu.be/Y1mwswiuung