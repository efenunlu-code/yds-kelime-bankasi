YDS KELİME BANKASI v1

Bu sürüm AI/API içermez. Kelimeler cihazda çalışır; arama ve favoriler localStorage ile tutulur.

Kaynak PDF: YDS / YÖKDİL Kelime Listesi
PDF başlığı 1492 kelime belirtmesine rağmen PDF hücrelerinden 1493 benzersiz kayıt çıkarıldı. Bu nedenle ilk sürümde kayıt silinmedi.

Dosyalar:
- index.html: web arayüzü
- words.js: kelime veri tabanı
- manifest.json: iOS ana ekrana ekleme/PWA bilgisi
- sw.js: çevrimdışı önbellek

iPhone:
1. Bu klasörü HTTPS çalışan bir web alanına yükle.
2. Safari ile index.html adresini aç.
3. Paylaş > Ana Ekrana Ekle.
4. Uygulama bağımsız uygulama görünümünde açılır.

Not: CodePen geliştirme için kullanılabilir; gerçek iPhone PWA kurulumu için GitHub Pages/Netlify/Vercel gibi HTTPS sunan bir yayın gerekir.

İleride aynı words.js veri yapısına yeni kelime kütüphaneleri eklenebilir.
