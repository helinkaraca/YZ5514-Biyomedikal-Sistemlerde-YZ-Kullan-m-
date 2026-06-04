# Meme Kanseri Sınıflandırma Projesi (Deep Learning)

## Proje Hakkında
Bu proje, meme kanseri histopatoloji görüntülerinin derin öğrenme yöntemleri kullanılarak sınıflandırılmasını amaçlamaktadır. Çalışmada modern Vision Transformer mimarileri olan **DeiT (Data-efficient Image Transformer)** ve **Swin Transformer** modelleri kullanılmıştır.

Amaç, farklı derin öğrenme modellerinin performanslarını karşılaştırarak tıbbi görüntü sınıflandırma problemine etkili bir çözüm sunmaktır.

---

## Kullanılan Modeller
- DeiT (Data-efficient Image Transformer)
- Swin Transformer

---

## Veri Seti
Bu çalışmada meme kanseri histopatoloji görüntülerinden oluşan bir veri seti kullanılmıştır. Görseller model girişine uygun hale getirilmek için ön işleme adımlarından geçirilmiştir.

---

## Yöntem

### 1. Veri Ön İşleme
- Görsellerin yeniden boyutlandırılması
- Normalizasyon işlemleri
- Veri artırma (data augmentation) teknikleri
- Eğitim / test veri ayrımı

### 2. Model Eğitimi
- Önceden eğitilmiş (pretrained) Vision Transformer modelleri kullanılmıştır
- Modeller veri setine göre fine-tuning yapılmıştır
- Optimizasyon için Adam optimizer kullanılmıştır

### 3. Değerlendirme
Modeller aşağıdaki metrikler ile değerlendirilmiştir:
- Accuracy (Doğruluk)
- Precision (Kesinlik)
- Recall (Duyarlılık)
- F1-score
- AUC (ROC eğrisi altında kalan alan)
- Dice Skoru
- IoU (Intersection over Union)

---

## Sonuçlar
Farklı transformer tabanlı modeller karşılaştırılmıştır. Elde edilen sonuçlar, Vision Transformer mimarilerinin tıbbi görüntü sınıflandırma problemlerinde yüksek başarı sağladığını göstermektedir.

---

## Kullanılan Teknolojiler
- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Proje Yapısı
