# Yerel Rotam — TÜBİTAK 2204 Lise Prototipi

Yerel Rotam, toplu taşıma kullanımını teşvik etmek amacıyla Yeşil Puan sistemi kullanan Android prototipidir.

## Özellikler
- Otobüs / metro / tren / tramvay yolculuğu ekleme
- Mesafeye göre otomatik puan: 0–15 km 1, 15–30 km 2, 30–50 km 3, 50+ km 5
- 50 puanda 1 ücretsiz biniş hakkı
- Profil, kart numarası ve demo bakiye alanları
- Yolculuk geçmişi
- İl içi liderlik tablosu
- Ay sonu 1./2./3. için +100/+75/+50 puan kuralı

## Önemli teknik not
Bu sürüm bir **TÜBİTAK prototipidir**. Gerçek ulaşım kartının bakiye/validasyon verisini otomatik okumak için ilgili belediye/ulaşım işletmesinin resmi API'si veya yetkili veri erişimi gerekir. Demo sürümünde kart bilgisi ve bakiye yerel olarak tutulur; kullanıcı yolculuk mesafesini manuel girer.

## Android Studio'da açma
Projeyi Android Studio ile açın. Gradle senkronizasyonundan sonra `app` modülünü çalıştırabilir ve `Build > Build APK(s)` ile APK oluşturabilirsiniz.

## Araştırma fikrinin bilimsel tarafı
Uygulamanın asıl TÜBİTAK değeri yalnızca yazılım değil, **ölçülebilir davranış değişikliği** deneyidir. Pilot grupta uygulama öncesi/sonrası toplu taşıma kullanım sıklığı, sürdürülebilir ulaşım farkındalığı ve kazanılan puanlar anonim olarak karşılaştırılabilir.
