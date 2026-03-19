🍽️ Dijital Yemek Tarifi Defteri (Digital Recipe Book)
Bu proje, kişisel yemek tariflerinizi dijital bir ortamda saklamanız, malzemeleri kategorize etmeniz ve tariflerinizi puanlamanız için geliştirilmiş Flask tabanlı bir web uygulamasıdır.

Uygulama, klasik bir defter tutma deneyimini modern web teknolojileri ve interaktif bir puanlama sistemiyle birleştirir.

🚀 Öne Çıkan Özellikler
📝 Dinamik Tarif ve Malzeme Kaydı
Akıllı Parçalama: Malzemeleri "Ürün: Miktar" formatında girerek otomatik liste görünümü oluşturma.

Kalıcı Depolama: Tüm tarif içerikleri ve hazırlama aşamaları SQLite veritabanında güvenle saklanır.

⭐ İnteraktif Puanlama Sistemi
Kullanıcı Değerlendirmesi: Her tarif için 1'den 5'e kadar puan verebilme imkanı.

Anlık Ortalama: Girilen her yeni puanla birlikte tarifin genel başarı puanı (ortalama) otomatik olarak yeniden hesaplanır.

🍱 Responsive Kart Tasarımı
Kayıtlı tarifler, sağ tarafta iştah açıcı "Tarif Kartları" şeklinde listelenir. Bu kartlar üzerinde yemeğin adı, malzemeleri, hazırlanışı ve güncel puanı anlık olarak görüntülenir.

🛠️ Teknik Altyapı
Proje, verimlilik ve hız odaklı bir teknoloji yığını üzerine inşa edilmiştir:

Backend: Python ve Flask framework'ü ile tüm iş mantığı ve veritabanı CRUD işlemleri yönetilir.

Veritabanı: İlişkisel veri modeli için SQLite3 kullanılmıştır. tarifler ve malzemeler tabloları arasında Foreign Key ilişkisi kurulmuştur.

Frontend: HTML5 ve CSS3 (Flexbox mimarisi) kullanılarak modern ve sıcak tonlarda bir kullanıcı arayüzü oluşturulmuştur.

Dinamik Veri Akışı: Backend'den gelen veriler Jinja2 motoru ile arayüze gerçek zamanlı olarak yansıtılır.

Çalıştırma Komutu
py app.py
