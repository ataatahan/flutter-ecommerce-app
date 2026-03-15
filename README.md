# 📱 Flutter E-Ticaret Uygulaması

Bu proje, Flutter kullanılarak geliştirilmiş bir **mobil e-ticaret uygulamasıdır**.  
Kullanıcılar ürünleri listeleyebilir, detaylarını inceleyebilir, sepete ekleyebilir ve sepet üzerinden ürünleri yönetebilir.  
Uygulama hem **iOS** hem de **Android** için isimlendirme özelleştirmeleri yapılmış şekilde çalışmaktadır.  

---

## 📝 Kısa Açıklama
- Modern ve kullanıcı dostu bir arayüz ile elektronik cihazların (iPhone, MacBook, iPad, AirPods vb.) listelenmesini sağlar.  
- Ürün detay sayfasında açıklama, fiyat ve görseller yer alır.  
- Sepet ekranında ürünler görüntülenebilir, çıkarılabilir ve checkout işlemi yapılabilir.  
- API üzerinden dinamik veri çekilerek ürünler güncel şekilde listelenir.  

---

## 🚀 Kullanılan Flutter Sürümü
Flutter 3.41.4 • channel stable  
Dart 3.11.1 • DevTools 2.54.1

---

## ⚙️ Çalıştırma Adımları
1. Bu repoyu klonlayın

2. Proje dizinine gidin: cd flutter-ecommerce-app

3. Gerekli paketleri yükleyin: flutter pub get

4. Uygulamayı çalıştırın: flutter run

🛠️ Kullanılan Teknolojiler ve Yapı

- Flutter & Dart → Mobil uygulama geliştirme için temel teknoloji.
- Stateful & Stateless Widgets → Dinamik ve statik ekran bileşenleri.
- API Entegrasyonu (REST API) →
- ApiService sınıfı ile https://wantapi.com/products.php adresinden ürün verileri çekilir.
- JSON verileri ProductModel sınıfı ile parse edilir.
- Model Yapısı (ProductModel, Meta, Data) → API’den gelen verilerin düzenli şekilde işlenmesi.
- UI Bileşenleri →
- HomeScreen: Ürün listeleme, arama, banner ve sepet yönlendirme.
- ProductDetailScreen: Ürün detayları, açıklama, fiyat ve sepete ekleme.
- CartScreen: Sepet yönetimi, ürün çıkarma ve checkout.
- ProductCard: Ürünlerin kart yapısında gösterimi.
- Navigasyon (Navigator) → Sayfalar arası geçiş.
- Hero Animasyonu → Ürün görsellerinde geçiş animasyonu.
- Material Design → Modern ve temiz arayüz tasarımı.

Ekran Görselleri
- Ana Sayfa (Discover): Ürünlerin listelendiği ekran
- Ürün Detay (Product Detail): Ürün açıklaması, fiyat ve sepete ekleme butonu
- Sepet (Cart): Sepete eklenen ürünlerin listelendiği ve checkout işleminin yapılabildiği ekran
- Sepet (Cart): Sepetin boş halinin görüntülendiği ekran

(Görselleri repo içineden screenshots/ klasöründen görüntüleyebilirsiniz)

📌 Notlar
- Android için APK derlemesi yapıldı (\build\app\outputs\flutter-apk) dilerseniz apk yı android telefonlarınıza kurabilirsiniz.
- iOS ve Android uygulama isimleri özelleştirildi.
- Proje Clean Architecture prensiplerine uygun şekilde katmanlı yapıda geliştirildi.
- Kod yapısı SOLID prensipleri gözetilerek düzenlendi.









