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
- Veri seti, farklı sınıflara ait görüntülerden oluşmaktadır.  
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

# 📌 Akbank Deep Learning Bootcamp: Next-Gen Project

## 🎯 Project Objective
The goal of this project is to develop an **image classification model** using a **Convolutional Neural Network (CNN)** architecture.  
Participants are expected to gain practical experience in the field of deep learning, including:  

- Image classification  
- Data analysis and preprocessing  
- Model development and optimization  
- Performance evaluation and interpretation  

---

## 📂 About the Dataset
- The dataset consists of images from multiple classes.  
- Images are split into **training, validation, and test sets**.  
- **Data augmentation techniques** (rotation, zoom, flip, color jitter, etc.) are applied to improve generalization.  
- **Class imbalance issues** are handled using *class weights* and augmentation strategies.  

---

## 🛠 Methods Used
- **CNN (Convolutional Neural Networks):** Feature extraction and classification from images  
- **Transfer Learning (EfficientNetB0):** Leveraging pre-trained models for better performance  
- **Data Preprocessing:** Image resizing, normalization, and augmentation  
- **Model Evaluation:**  
  - Accuracy, Precision, Recall, F1-Score  
  - Confusion Matrix & Heatmap visualizations  

---

## 📊 Results
- The model was successfully trained and achieved **high accuracy on the test set**.  
- **EarlyStopping** and **ModelCheckpoint** callbacks were applied to prevent overfitting.  
- Results were presented using **metrics and visualization plots**.  

---

## 🚀 Future Work
- Training with larger and more diverse datasets  
- Comparison with other CNN architectures (ResNet, DenseNet, VGG)  
- Testing the model in **real-world scenarios**  

---


