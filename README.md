# KodluyoruzBitirmeProjesi
# Küresel Sürdürülebilir Enerji Verileri ile Ülke Bazlı Enerji Risk Skorunun Analizi ve Tahminlenmesi


Bu proje, Kodluyoruz W-Code 2.0 Veri Bilimi ve Yapay Zeka Atölyesi kapsamında
geliştirilmiştir. Amaç, ülkelerin enerjiye erişim ve sürdürülebilirlik
göstergelerini kullanarak bir enerji risk skoru oluşturmak ve bu skoru
makine öğrenmesi modelleri ile Low / Medium / High risk sınıflarına
otomatik olarak ayırmaktır.

---

## 🎯 Projenin Amacı
- Enerjiye erişim ve sürdürülebilirlik verilerinden anlamlı bir risk skoru üretmek
- Ülkeleri enerji risk seviyelerine göre sınıflandırmak
- Farklı makine öğrenmesi modellerini karşılaştırmak
- Model performansını uygun metriklerle değerlendirmek
- Sonuçları görselleştirerek anlaşılır hale getirmek

---

## 🧠 Problem Tanımı
Bu proje, çok sınıflı (multiclass) bir sınıflandırma problemidir.

Modelin görevi:
> Enerji göstergelerine bakarak bir ülkenin enerji risk seviyesini  
> **Low – Medium – High** olarak tahmin etmek.

---

## 📊 Kullanılan Özellikler (Features)
- Elektrik erişim açığı
- Temiz yakıt erişim açığı
- Enerji yoğunluğu
- Yenilenebilir enerji payı
- Kişi başı enerji tüketimi

---

## ⚙️ Makine Öğrenmesi Süreci
- Veri temizleme ve ön işleme
- StandardScaler ile ölçeklendirme
- Label Encoding
- Stratified Train-Test Split (%75 / %25)
- Modelleme ve karşılaştırma
- GridSearchCV ile hiperparametre optimizasyonu

---

## 🤖 Kullanılan Modeller
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost

---

## 📈 Değerlendirme Metrikleri
- Accuracy
- F1-macro

---

## 🔍 Model Analizi
- Feature Importance
- Confusion Matrix
- ROC – AUC analizi

---

## 📊 Görselleştirme
- Matplotlib
- Seaborn
- Dünya haritası üzerinde risk dağılımları

---

## 🛠️ Kullanılan Teknolojiler
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 👥 Ekip
- 3 kişilik ekip çalışması kapsamında geliştirilmiştir.

---

## 📌 Not
Bu proje, eğitim amaçlı geliştirilmiş olup veri bilimi ve makine öğrenmesi
pipeline’ını uçtan uca uygulamayı hedeflemektedir.
