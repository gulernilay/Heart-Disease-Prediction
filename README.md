# Heart-Disease-Prediction

Bu proje, Framingham veri seti kullanılarak bireylerin 10 yıl içinde kalp hastalığına yakalanma riskini tahmin etmeye yönelik bir veri analizi ve makine öğrenmesi çalışmasıdır.
Veri seti Linki :https://www.kaggle.com/datasets/noeyislearning/framingham-heart-study

## Proje İçeriği

- **Veri Yükleme ve Ön İşleme:** Eksik verilerin doldurulması, veri tiplerinin kontrolü ve temel istatistiklerin çıkarılması.
- **Keşifsel Veri Analizi (EDA):** Veri setindeki değişkenlerin dağılımı, ilişkileri ve kalp hastalığı ile bağlantıları görselleştirilmiştir.
- **Görselleştirme:** Farklı grafikler ile verinin daha iyi anlaşılması sağlanmıştır.
- **Makine Öğrenmesi:** (Eklenebilir) Farklı algoritmalar ile kalp hastalığı tahmini.

## Kullanılan Kütüphaneler

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

## Dosya Açıklamaları

- **main.ipynb:** Tüm analiz ve görselleştirme adımlarının bulunduğu Jupyter Notebook dosyası.
- **framingham.csv:** Framingham kalp hastalığı veri seti.

## Veri Seti Özellikleri

Veri setinde yer alan bazı önemli sütunlar:

- `age`: Yaş
- `male`: Cinsiyet (1: Erkek, 0: Kadın)
- `education`: Eğitim seviyesi
- `currentSmoker`: Şu anda sigara içiyor mu
- `cigsPerDay`: Günlük içilen sigara sayısı
- `BPMeds`: Tansiyon ilacı kullanımı
- `prevalentStroke`: Geçmişte felç geçirmiş mi
- `prevalentHyp`: Yüksek tansiyon var mı
- `diabetes`: Diyabet var mı
- `totChol`: Toplam kolesterol
- `sysBP`: Sistolik kan basıncı
- `diaBP`: Diyastolik kan basıncı
- `BMI`: Vücut kitle indeksi
- `heartRate`: Kalp atış hızı
- `glucose`: Glikoz seviyesi
- `TenYearCHD`: 10 yıl içinde koroner kalp hastalığı gelişimi (hedef değişken)

## Görselleştirme Örnekleri

- **Histogram:** Yaş dağılımı ve kalp hastalığı durumu
- **Boxplot:** BMI ve kalp hastalığı ilişkisi
- **Pairplot:** Seçili değişkenler arası ilişkiler
- **Countplot:** Eğitim seviyelerine göre kalp hastalığı dağılımı
- **Violin Plot:** Kolesterol dağılımı
- **Pie Chart:** Kategorik değişkenlerin oranları (cinsiyet, diyabet, sigara kullanımı vb.)
- **Barplot:** Kalp hastalığına etki eden değişkenlerin ortalama değerleri
- **Scatterplot:** Erkek ve kadınlarda kalp atış hızı ile kolesterol ilişkisi
- **Heatmap:** Tüm değişkenler arasındaki korelasyonlar

## Kurulum ve Kullanım

1. Gerekli kütüphaneleri yükleyin:
   ```
   pip install pandas numpy seaborn matplotlib
   ```
2. `main.ipynb` dosyasını Jupyter Notebook veya VS Code ile açın.
3. Hücreleri sırasıyla çalıştırarak analizleri ve görselleştirmeleri inceleyin.

## Katkı Sağlama

Katkı sağlamak için lütfen bir fork oluşturup pull request gönderin.

## Lisans

MIT Lisansı altında sunulmuştur.
