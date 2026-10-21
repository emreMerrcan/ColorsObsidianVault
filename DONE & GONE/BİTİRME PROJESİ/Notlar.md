EL konumuna bağlı cursor hareketi yapacağında, bunu elin boyutuna oranlayarak yap. Yani elin genişliği X uzunlukta ise, her X birim hareket oyun dünyasına sabit aktarılacak. Böylece kullanıcı uzakta olsa, yakın da olsa el hareketinin etkisi aynı olacağından oyuncular mesafeden bağımsız stabil bir yönetim deneyimi elde edebilecek.

Üç proje modeli var elimde:

En hızlısı: MediaPipe + MLP custom labeler üzerine pozisyon sensitive controller algoritmaları yazıcam

En optimal: Custom modeli güzelce eğitip mediapipe ı aradan çıkarıcam

En Sağlamı (ama iffy): CNN+LSTM ile dinamik tamamlama cart curta ihtiyacım olacak.


GELECEK:
Görsel deneme
Dataset büyütme
Parmak farklarını ekleme
Büyük dataset kullanma


EL İŞARETLERİ:

1 İşaret parmağı
2 Barış işareti
3 El açık
4 Yumruk
5 baş parmak kalkık
6 serçe parmak kalkık
7 serçe ve baş kalkık
8 rocnroll
9 işaret baş kalkık
0 üç parmak kalkık

11 baş işaret ve orta kalkık
12 orta parmak
13 top işareti (diğer üç bitişik)
14 parmaklar dik ama büzüşük
15 el full açık sadece başparmak kapalı
16 

POZ TAKİPLERİ:
1.  Parmak ucu YA DA parmak rotasyonu
2.  Parmaklar arası mesafe
3.  El rotasyonu
4.  Pozisyon
5.  Parmak rotasyonu YA DA uç pozisyonu
6.  Pozisyon
7.  Pozisyon
8.  Pozisyon
9.  Parmaklar arası mesafe
10. Parmaklar arası mesafe toplamı



Wonderful. Now further expand on the script by adding these gestures too:
0- Cursor at the keypoint 8 and the gap between fingertips, keypoint 8-12 and 12-16 are printed.
2- Cursor at the keypoint 8, print the distance between keypoint 8 and 12
3- Cursor at the keypoint 8, and print the degree of hand rotation (vector drawn between keypoint 0 and 9)
4- Cursor at the keypoint 8. 
5- Cursor at the keypoint 4, finger direction (vector between keypoint 2 and 4)
6- Cursor at the keypoint 20
7- Cursor at the keypoint 20
8- Cursor at the keypoint 8
9- Cursor at the keypoint 8 and the distance between keypoint 4 and 8
Note: All the values should be taken after the normalisation except the rotation and vector stuff.
