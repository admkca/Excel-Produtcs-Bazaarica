# Bazaarica Excel Products

## 📅 Proje Amacı
Bu proje, Excel dosyasından ürün bilgilerini (barkod, ürün ismi ve resimler) hızlı bir şekilde web ortamına aktarıp yönetebilmek için geliştirildi. 
Kullanıcılar bir Excel dosyası yükleyerek ürünlerini listeleyebilir, ürünler arasında arama yapabilir, resimleri önizleyebilir ve verileri tekrar Excel dosyası olarak dışa aktarabilir.

## 🌟 Özellikler
- Excel (.xlsx / .xls) dosyası yükleyerek veri listeleme
- Ürünler üzerinde barkod veya ürün ismine göre canlı arama filtresi
- Ürün resimlerini modal pencerede önizleme
- Ürün resimleri üzerinden tekil resim silme
- Listeyi Excel formatında tekrar dışa aktarabilme (Export)
- Yüklenme ve işlem sürelerini kullanıcıya bildirme
- Bootstrap 5 kullanılarak responsive (mobil uyumlu) tasarım

## 🔧 Kullanılan Teknolojiler
- HTML5
- CSS3 (Bootstrap 5 ile responsive tasarım)
- JavaScript (Vanilla JS)
- [xlsx](https://cdnjs.com/libraries/xlsx) kütüphanesi (Excel dosyası okumak için)
- [ExcelJS](https://cdnjs.com/libraries/exceljs) kütüphanesi (Excel dosyası yazmak için)
- Bootstrap Modal kullanılarak resim önizleme

## 🚀 Kurulum

1. Proje dosyalarını bilgisayarına indir.
2. `index.html` dosyasını bir tarayıcıda (Örn: Chrome) aç.
3. Excel dosyası yükleyerek ürünlerini yüklemeye başla.

**Not:** Proje tamamiyle frontend (ön yüz) tabanlıdır. Herhangi bir backend sunucu gerektirmez.


## 📍 Yapı
```
/index.html      → Ana proje dosyası
/css             → Bootstrap CDN ile bağlantı
/js              → xlsx.js ve exceljs.js CDN bağlantıları
```

## 🔍 Geliştirme Planları (Opsiyonel)
- Offline çalışacak PWA yapısı eklenmesi
- Çoklu sayfa desteği (Pagination)
- Backend ile veri kaydı (Node.js / Firebase vb.)

---

Hazırlandı: **Adem KOCA 🌟**
