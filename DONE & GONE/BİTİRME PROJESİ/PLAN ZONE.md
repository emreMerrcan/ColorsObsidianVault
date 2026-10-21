### Tamamlama Tarihleri
- [x] Diary şema çıktısı ve sahte girdiler, MediaPipe tam kurulum ve nasıl kullanılır çözümü - 23
- [x] Enver hoca ziyaret - 1
- [x] Dataset oluşturmak için gerekli yazılım alt yapısını oluştur ve GRU ML'i traininge hazır hale getir- 6 Nisan
- [x] İki sistemi de optimize et, training sonuçlarını ve isabet oranlarını, performanslarını çıktıla ve kıyasla- 10 Nisan
- [x] Raporu hazırla - 15 Nisan
- [ ] Parmak aralıklarının hesabını tuttuğun girdileri de dahil ederek yeni bir dataset oluştur, eğit, test et - 18 Nisan
- [ ] Image tabanlı modeli yap ve dataset kaydedip eğit, testet - 19 Nisan
- [ ] Modellerin optimizasyonu için araştırma yap, MLP'nin max performansını ortaya çıkar 20-21 Nisan
- [ ] Large dataset bul veya üret, modeli her açıya yüksek isabet yakalayacağı şekilde eğit 21-23 Nisan
- [ ] Inference çıktısını aracı bir yazılıma aktar, mouse u nasıl hareket ettireceğin, işletim sistemi seviyesinde komut yorumlama algoritmasını nasıl oturtacağını çöz - 24-28 Nisan
- [ ] Bu çıktıyı unreal a bağla 29-30
- [ ] Tümüyle fonksiyonel bir el iskeleti çıktısı yazılımı ve classifed gesture, aracı yazılımla Unreal Engine'a aktarılsın ve debuga print versinler - Nisan 30




- [ ] 26 unity den debug al  
- [ ] 27 unreal çöz ve yarın için zemin kur,  
- [ ] 28 bir parmak pozisyonununu bir objenin pozisyonuna bağla  
- [ ] 29 parmak pozisyonlarına küreler bağla ve oyun uzayında pozisyon göstersinler  
- [ ] 30 piyano mantığını kodla ve sesleri ekle, çalabiliyor ol  
- [ ] 31-1 araba oyununu yap ve el komutlarıyla vites, yön, fren, turbo vesaire işini entegre et  
- [ ] iş haftası içinde objektifler: Unreal integration polish, operating system integration comprehensive polish, redesign mapping and make it so that (almost) every button is accessible




YOLO CAPTURER:
Jupyter la çalışıyo galiba ancak indirip VSCODE ortamında açarsan yine uzantıları bağlayıp çalıştırabiliyorsun sanırım, kod videoda gözüktüğü gibi, anladığım kadarıyla kırpıyosun ve o da anında bazı feature ları kapıyo.

OK AS IT TURNS OUT, videoya bile ihtiyacım yok eğer kepoint position relation'larını kullanacaksam ki bence öyle yapmalıyım. KEYPOINTS and THE LABEL, bu iki veriye ihtiyacım var. Ardından GRU'ya full keypoint sokup neticede label'ını da vererek eğitilmesini sağlicam. Böylece kendisi label tahmin edebilir olacak.



Cursor'un önerisi, yalnızca parmakların pozisyonlarını değil, aralarındaki mesafelere de sayı atayıp takibini tuttur, bence mantıklı. Her parmak ucunun kökünden uzaklığı (açıklık seviyesi yani) ve uçların komşularından uzaklığı (yakınlık), ardından da palm root tan uzaklığı (tüm el açıklığı)


Dataset: Video, gestures, rgb camera
Code the fucking LSTM
MediaPipe connect to LSTM
Code the fucking CNN
Preprocessing
EHMMM.......
Action localization

**Linalg.norm usage:** I used `np.linalg.norm` on the already normalized `rel` coordinates. This ensures these distances are **scale-invariant** (the distances won't change just because your hand is closer to the camera).

### Önerilmiş Plan
February:
- [ ] Design a Project Development Diary document format and create it.
March: 
- [ ] Gathering necessary sources, datasets, tools and the work environment.
- [ ] Design and implement image processing algorithm to normalize dataset input
- [ ] Setup the MediaPipe hand pose extraction model and customize
- [ ] Test, validate and model 3D skeletal visualization in real-time
April: 
- [ ]  Code and initialize the hand gesture classification model
- [ ] Testing, validating and optimizing the model for responsive outputs 
- [ ] Extract outputs with PyTorch for input testing
May: 
- [ ] Design and create an input system and control map on Unreal Engine
- [ ] Design and create the Timing Based Platformer game for gesture input testing
- [ ] Design and create the Piano Tiles game for hand position input testing
June: 
- [ ] Design and create the Car Race game for both gesture and hand position input testing
- [ ] Design a survey on performance, analysis and user experience
- [ ] Test all 3 projects on a tester sample of people
- [ ] Last iteration for model improvements based on user grading and improvement of the games for better testing
- [ ] Finalizing the report and the Project Development Diary
- [ ] Finalize the project by uploading it various platforms accessible to the public