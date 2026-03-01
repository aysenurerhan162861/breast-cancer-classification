# 🔬 Meme Kanseri Sınıflandırması

Bu proje, makine öğrenmesi dersi kapsamında hazırlanmıştır.

## 📌 Proje Hakkında
Breast Cancer Wisconsin veri seti kullanılarak meme kanseri 
tümörlerini iyi huylu (Benign) ve kötü huylu (Malignant) olarak 
sınıflandıran bir model geliştirilmiştir.

## 📊 Veri Seti
- **Ad:** Breast Cancer Wisconsin Dataset
- **Kaynak:** UCI Machine Learning Repository
- **Satır sayısı:** 569 hasta kaydı
- **Öznitelik sayısı:** 30 sayısal öznitelik
- **Sınıflar:** Benign (İyi Huylu) - 357, Malignant (Kötü Huylu) - 212
- **Eksik veri:** Yok

## ⚙️ Kullanılan Yöntem
**Random Forest (Rastgele Orman)** algoritması kullanılmıştır.

## 📈 Sonuçlar
| Metrik | Sonuç |
|--------|-------|
| Accuracy | %97.37 |
| Precision | %100.00 |
| Recall | %92.86 |
| F1-Score | %96.30 |

## 📁 Dosyalar
- `breast_cancer_classification.ipynb` → Kodlar ve açıklamalar
- `data.csv` → Veri seti

## 🛠️ Kullanılan Kütüphaneler
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
