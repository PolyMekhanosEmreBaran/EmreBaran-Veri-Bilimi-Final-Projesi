# BIST 6 Hisse Senedi Veri Bilimi ve Modelleme Projesi

Bu proje, İstanbul Üniversitesi-Cerrahpaşa Bilgisayar Mühendisliği Bölümü Veri Bilimi Dönem Projesi kapsamında geliştirilmiştir. Projede Borsa İstanbul'da yer alan 6 farklı hissenin uçtan uca veri bilimi iş akışı (Veri temizleme, EDA, Görselleştirme ve Modelleme) uygulanmıştır.

## Proje Ekibi
Adı Soyadı:Emre Baran
Öğrenci Numarası:1306240007

## Teknik Kapsam & Yapılanlar
1. **Veri Ön İşleme:** `Date` string/int formatından datetime formatına çekildi. Eksik veriler `ffill` ile tamamlandı, tekrarlı veriler drop edildi.
2. **EDA (Keşifsel Veri Analizi):** 3 adet finansal araştırma sorusu tanımlandı. Matplotlib ve Seaborn ile 4 farklı grafik türü üretildi.
3. **Modelleme:** THYAO hissesi için son 5 günün verilerine dayanarak yarınki fiyatı tahmin eden `Linear Regression` modeli eğitildi. ($R^2$: 0.9984, MAE: 3.86 TL)

## Kullanılan Kütüphaneler
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

## Nasıl Çalıştırılır?
1. Bu repoyu bilgisayarınıza indirin.
2. Gerekli kütüphaneleri yükleyin: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Klasörde ilgili CSV dosyalarının bulunduğundan emin olun.
4. `Jupyter Notebook` veya `VS Code` üzerinden `.ipynb` dosyasını sırasıyla çalıştırın.

## Veri Kaynağı & Lisans
* **Kaynak:** Kaggle - BIST 100 Historical Data
* **Lisans:** Open Data Commons Attribution License (ODC-By)
