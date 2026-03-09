# 🚗 Car Price Prediction System

## Proje Tanımı
Bir otomotiv şirketinin araç özelliklerine bakarak 
ikinci el araba fiyatlarını tahmin eden TensorFlow tabanlı 
bir regresyon sistemi.

## 📊 Model Sonuçları
- **Test MAE:** 3.953€ (ortalama tahmin hatası)
- **Örnek Tahmin:** 2019 model, 15.000 km, 2.0 motor → 26.089€

## 📁 Dosya Yapısı
tensorflow_car_price_prediction.ipynb
merc.xlsx

## 🛠️ Kullanılan Teknolojiler
- **TensorFlow/Keras** → Regresyon modeli
- **Pandas** → Veri okuma ve işleme
- **Scikit-learn** → Normalizasyon, train/test ayırma
- **NumPy** → Sayısal işlemler

## 📌 Sistem Akışı
1. Kaggle'dan gerçek Mercedes veri seti kullanıldı
2. Transmission kolonu encode edildi
3. MinMaxScaler ile normalizasyon yapıldı
4. 3 katmanlı Dense sinir ağı eğitildi
5. Yeni araç için fiyat tahmini yapıldı