# Robotik-Goruntu-Isleme-ve-Nesne-Tanima-icin-Parametre-Analizi
# Robotik Görüntü İşleme ve Nesne Tanıma için Parametre Analizi

Bu proje, robotik görü sistemlerinde kullanılan görüntü işleme boru hattının (pipeline) performansını, parametre optimizasyonu üzerinden inceleyen bir araştırma ve uygulama çalışmasıdır. Proje, görüntü ön işlemeden öznitelik çıkarımına kadar olan süreçteki kritik parametrelerin (Gauss, CLAHE, Canny, ORB) çıktı kalitesi üzerindeki etkilerini nicel verilerle analiz eder.

## 🛠️ Kullanılan Teknolojiler

- **Dil:** Python 3.x
- **Kütüphaneler:**
  - `OpenCV`: Görüntü işleme ve öznitelik çıkarma.
  - `NumPy`: Matris operasyonları.
  - `Matplotlib`: Sonuçların görselleştirilmesi.
  - `Pandas`: Deney sonuçlarının tablolaştırılması.

## 📋 İşlem Hattı (Pipeline)

Proje akışı şu adımlardan oluşmaktadır:
1. **Gri Seviye Dönüşümü:** Görüntünün işleme hızı için basitleştirilmesi.
2. **Gaussian Smoothing:** Gürültü bastırma.
3. **CLAHE:** Yerel kontrast iyileştirme.
4. **Canny Edge Detection:** Kenar ve sınır tespiti.
5. **Kontur Analizi:** Alan ve dairesellik (circularity) filtrelemesi.
6. **ORB Feature Extraction:** Anahtar nokta (keypoint) tespiti.

## 📊 Deney ve Bulgular

Proje kapsamında 5 farklı konfigürasyon test edilmiştir. Temel çıkarımlar şunlardır:

| Parametre Değişimi | Gözlemlenen Etki |
| **CLAHE ClipLimit 
| **Gaussian Sigma 
| **Canny Eşikleri 
| **ORB Kararlılığı

