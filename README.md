# 📊 Excel Finansal Analiz Dashboard (VBA ile)

Bu projede, hisse senedi bazlı finansal analiz yapmak amacıyla oluşturulmuş profesyonel bir Excel Dashboard yer alıyor. VBA makroları ile desteklenen bu sistem, veri yükleme, tablo temizleme ve PDF çıktısı alma gibi otomasyonlar içeriyor.

# ⚠️ Önemli !

Şirketlerin mali tablolarını "www.isyatirim.com.tr" üzerinden almalısınız. Kullanılan formüller buradaki tablolara göre ayarlanmıştır.
Ayrıca finansal şirketlerin mali tabloları farklı yapıya sahip olduğu için bu yapıya uygun değildir. Kendiniz "analiz" sekmesindeki tablo hücrelerindeki formülleri tekrar düzenleyerek yapabilirsiniz. 

![işbankası](https://github.com/user-attachments/assets/0b328628-28b0-42a8-80bf-c085566025bd)



## 📌 Özellikler

- ✅ Likidite, kârlılık, mali yapı gibi oranların otomatik hesaplanması
- 📈 Grafiklerle desteklenen analiz ekranı
- 🔄 Otomatik yorumlamalar ve açıklamalar
- 📤 PDF çıktısı alma 
- 📥 Excel dosyasından veri yükleme
- 📊 Midas'tan alınan anlık Bist verileri ile şirketin hisse fiyatı
- 📊 Uzman Para sitesinden her 5 dk da bir alınan verilerle Bist'de en çok artan / azalan 5 hissenin tablosu  

## 📷 Ekran Görüntüleri

![3](https://github.com/user-attachments/assets/7866c182-92c2-4e2d-9fe5-02e360586006)             

![1](https://github.com/user-attachments/assets/278d14ec-8018-44a4-8a45-ce379df55802)

![2](https://github.com/user-attachments/assets/8ca909a8-bd05-45d1-bd6e-21d94cc7f7b5)

## 📄 Makrolar ve Açıklamaları

### 1. PDF Kaydetme Makrosu
`PdfKaydet.txt`  
📄 Analiz sayfasını PDF olarak dışa aktarır. Kullanıcıdan kayıt yeri ve isim ister.

### 2. Veri Yükleme Makrosu  
`DosyaYukleme.txt`  
📥 Başlıklar dahil yeni bir Excel dosyasından veri alır ve hedef sayfadaki tabloya yapıştırır.

### 3. Tablo Temizleme Makrosu  
`TabloVerileriSil.txt`  
🧹 Tablodaki tüm verileri siler ama tablo yapısını korur. “Yapıyı bozmadan sıfırla” çözümüdür.

---


---

## 👨‍💻 Geliştirici

Akif
GitHub: [github.com/AKT-TR](https://github.com/AKT-TR)

---

## 📬 Lisans

Bu proje açık kaynak olup dilediğiniz gibi kullanabilirsiniz. Lisans dosyası dahil değildir.

