# 📈 Store Sales Forecasting Analysis (Mağaza Satış Tahminleme Analizi)

Bu proje, mağazaların haftalık satış rakamlarını etkileyen faktörleri (ekonomik göstergeler, sıcaklık, tatil günleri vb.) analiz ederek makine öğrenmesi modelleri ile geleceğe yönelik satış tahminleri yapmayı amaçlar.

## 🚀 Proje Özeti
Perakende sektöründe doğru stok yönetimi ve finansal planlama için satış tahmini kritik öneme sahiptir. Bu projede, 45 farklı mağazanın geçmiş verileri kullanılarak regresyon analizi yapılmış ve satışları etkileyen temel faktörler incelenmiştir.

## 📊 Veri Seti ve Özellikler
Veri seti aşağıdaki temel değişkenleri içermektedir:

* **Store:** Mağaza numarası
* **Weekly_Sales:** Hedef değişken (Haftalık Satış Miktarı)
* **Holiday_Flag:** Tatil haftası olup olmadığı (0/1)
* **Temperature:** Bölgesel sıcaklık
* **Fuel_Price:** Bölgedeki yakıt fiyatı
* **CPI (Tüketici Fiyat Endeksi):** Enflasyon göstergesi
* **Unemployment:** İşsizlik oranı

## 🛠️ Kullanılan Teknolojiler ve Yöntemler
* **Python:** Veri analizi ve modelleme
* **Pandas & NumPy:** Veri manipülasyonu
* **Scikit-Learn:** Makine öğrenmesi algoritmaları
* **Matplotlib & Seaborn:** Veri görselleştirme

### Uygulanan Adımlar:
1.  Veri Keşfi (EDA) ve Temizleme
2.  Outlier (Aykırı Değer) Analizi
3.  Öznitelik Mühendisliği (Feature Engineering)
4.  Model Eğitimi (Decision Tree Regressor)

## 📈 Model Sonuçları

Projede **Decision Tree Regressor** kullanılarak elde edilen test sonuçları aşağıdadır:

| Metrik | Değer |
| :--- | :--- |
| **R2 Score** (Açıklayıcılık Katsayısı) | **0.896** (%89.6) |
| **MAE** (Ortalama Mutlak Hata) | **96,110** |
| **MSE** (Ortalama Kare Hata) | **33,218,381,258** |

Model, satışlardaki varyasyonun yaklaşık **%90'ını** başarıyla açıklamaktadır.


