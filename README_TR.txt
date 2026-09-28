YDS KELİME BANKASI v5
======================

Bu sürüm GitHub Pages / PWA olarak çalışır.

İÇERİK
- Kullanıcının verdiği YDS/YÖKDİL PDF'sinden çıkarılmış 1493 benzersiz kelime/ifade.
- 60+ -> 70+ -> 85+ -> 90+ -> 95+ -> 100 kademeli yapı.
- Yerel hafıza ve aralıklı tekrar.
- Yanlışlar için ayrı tekrar oturumu.
- 5 soru tipi: EN→TR, TR→EN, Anlam→Kelime, Bağlam, Anlam Ayırt Etme.
- İstendiği zaman açılabilen 40 soruluk / 40 dakikalık kelime deneme sınavı.
- Deneme sonuçları cihazın localStorage alanında tutulur.
- Koyu/dark tema.
- OpenAI API veya başka ücretli API kullanılmaz.

VERİ SETİ NOTU
PDF kapağında "1492 kelime" yazsa da veri çıkarımı sonucunda 1493 benzersiz kelime/ifade elde edilmiştir. Sütun başlıkları veri olarak sayılmamıştır. Bu nedenle 1493 kayıt korunmuştur; yapay olarak 2000'e tamamlanmamıştır.

GITHUB PAGES
- Tüm dosyaları repository'nin ana dizinine yükleyin.
- Settings > Pages > Deploy from a branch > main > /(root).
- index.html ana dizinde kalmalıdır.
- Güncellemeden sonra eski PWA önbelleği görülürse sayfayı tamamen yenileyin veya service worker/site verisini temizleyin.
