# deep-learning-bootcamp-project
CNN tabanlı görüntü sınıflandırma projesi | Akbank Derin Öğrenme Bootcamp  
(Deep learning project for image classification using CNN (Bootcamp Project) )

# 📌 Akbank Derin Öğrenme Bootcamp: Yeni Nesil Proje

## 🎯 Projenin Amacı
Bu projenin amacı, **Convolutional Neural Network (CNN)** mimarisi kullanarak bir görüntü sınıflandırma modeli geliştirmektir.  
Katılımcıların derin öğrenme alanında:  

- Görüntü sınıflandırması  
- Veri analizi ve ön işleme  
- Model geliştirme ve iyileştirme  
- Modelin performansını değerlendirme ve yorumlama  

konularında **pratik deneyim kazanması** hedeflenmektedir.  

---

## 📂 Veri Seti Hakkında
- Bu veri yaklaşık 25.000 adet 150x150 boyutunda görüntü içeriyor ve 6 kategoriye dağıtılmış durumda.
{'buildings' -> 0,
'forest' -> 1,
'glacier' -> 2,
'mountain' -> 3,
'sea' -> 4,
'street' -> 5 }
- Görseller **eğitim, doğrulama ve test seti** olarak ayrılmıştır.  
- **Data augmentation (rotation, zoom, flip, color jitter vb.)** teknikleri kullanılarak modelin genelleme kabiliyeti artırılmıştır.  
- **Sınıf dengesizliği** problemlerine karşı *class weight* ve ek veri artırma yöntemleri uygulanmıştır.  

---

## 🛠 Kullanılan Yöntemler
- **CNN (Convolutional Neural Network):** Görsellerden öznitelik çıkarımı ve sınıflandırma  
- **Transfer Learning (EfficientNetB0):** Daha güçlü performans için önceden eğitilmiş model kullanımı  
- **Veri Ön İşleme:** Görsellerin yeniden boyutlandırılması, normalizasyonu ve veri artırma işlemleri  
- **Model Değerlendirme:**  
  - Accuracy, Precision, Recall, F1-Score  
  - Confusion Matrix & Heatmap görselleştirmeleri  

---

## 📊 Elde Edilen Sonuçlar
- Model başarıyla eğitilmiş ve **test verisi üzerinde yüksek doğruluk oranı** elde edilmiştir.  
- Eğitim sürecinde **EarlyStopping** ve **ModelCheckpoint** yöntemleri ile aşırı öğrenme (*overfitting*) önlenmiştir.  
- Sonuçlar, **grafikler ve metriklerle görselleştirilmiştir.**  

---

## 🚀 Gelecek Çalışmalar
- Daha büyük ve çeşitli veri setleri ile modelin eğitilmesi  
- Farklı CNN mimarilerinin (ResNet, DenseNet, VGG) karşılaştırılması  
- Modelin **gerçek dünya senaryolarında test edilmesi**  

-----------------------------------------------------

# Kaggle:https://www.kaggle.com/code/ferideuum/deeplearningbootcampproject
