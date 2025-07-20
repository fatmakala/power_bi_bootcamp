

## DANONE Power BI Satış Analizi Projesi

### 📌 Proje Amacı

Bu proje, Power BI kullanarak DANONE markasına ait satış verilerini analiz etmek, müşteri davranışlarını anlamak ve kategori bazlı stratejik çıkarımlar sunmak amacıyla hazırlanmıştır. Veriler üzerinde temizlik, modelleme, hesaplamalar ve görselleştirme adımları gerçekleştirilmiştir.

### 🗃️ Kullanılan Veriler

| Tablo Adı         | İçerik                                   |
|-------------------|-------------------------------------------|
| `kullanıcılar`    | Müşteri bilgileri (yaş, cinsiyet, şehir)  |
| `siparis`         | Sipariş bilgileri (tarih, adres, müşteri) |
| `siparisdetay`    | Ürün ve miktar bilgileri                  |
| `items`           | Ürün kataloğu (marka, kategori, fiyat)    |
| `adres`           | Şehir ve konum bilgileri                  |
| `bölgeler`        | Şehir-bölge eşlemesi                     |


### 🧠 Uygulanan Dönüşümler

- Doğum tarihinden yaş ve yaş grubu hesaplandı
- Cinsiyet, isim sütunundan çıkarıldı
- Tarih kolonundan saat ve hafta tipi bilgisi ayrıldı
- İstanbul’da oturan genç müşteri grubu filtrelendi
- Tablolar arası modelleme (birden çoğa ilişkiler) kuruldu
- Gereksiz kolonlar kaldırıldı (`CREATEDDATE`, `TELNR2` vb.)


### 🛢️ Oluşturulan Ölçüler

- **Toplam Satış Adeti**  
- **Toplam Ciro**  
- **Toplam Sipariş Sayısı**  
- **Toplam Müşteri Sayısı**  
- **Müşteri Başına Ciro ve Adet**  
- **Ortalama Sipariş Tutarı**  
- **Saatlik Satış Tutarı**  
- **Haftaiçi / Haftasonu Satış Analizi**  
- **Yaş Grubu Bazlı Satış**


### 📊 Sayfa Yapısı

| Sayfa | İçerik |
|-------|--------|
| **Giriş** | Rapor başlığı, sayfa geçiş butonları  |
| **Özet** | Haftaiçi/sonu satış grafiği, saatlik satış, toplam ölçüler  |
| **Müşteri Perspektifi** | Kadın/erkek sayısı, yaş grubuna göre satış, top 10 müşteri  |
| **Kategori Perspektifi** | İstanbul + Genç grubunun cirosu → kategori bazlı ağaç haritası  |


### 📌 Rapor Özeti

Bu rapor sayesinde:
- En çok satış yapılan saatler ve günler tespit edildi  
- Genç müşteri kitlesinin ürün eğilimleri analiz edildi  
- Bölgelere göre satış dağılımı görselleştirildi  
- Kategori bazında satış stratejileri oluşturulabilir hale geldi

  > Not: .pbix dosyası GitHub üzerinde büyük olduğu için görüntülenememektedir. Lütfen indirip Power BI Desktop ile açınız.



### ✨ Hazırlayan

**Fatma Kala**  
Power BI Bootcamp – Bitirme Projesi  
Temmuz 2025






