# cnn-bootcamp
# Intel Image Classification – CNN Bootcamp Project

---

##  Veri Seti
- Dataset: Intel Image Classification (6 sınıf : Buildings, Forest, Glacier, Mountain, Sea, Street)  
- Eğitim ve doğrulama (train/validation) setlerine ayrılmıştır.  
- Data Augmentation: rotation, shift, zoom, horizontal flip uygulanmıştır.  

---

## Model Mimarisi
- Conv2D + MaxPooling katmanları (özellik çıkarımı)  
- Flatten (düzleştirme)  
- Dense katmanları (tam bağlı)  
- Dropout (overfitting’i önlemek için)  
- Çıkış katmanı (softmax, 6 sınıf)  

Optimizer: **Adam**  
Loss: **Categorical Crossentropy**  
Metric: **Accuracy**

---

## Sonuçlar
- Validation Accuracy: **~87%**  
- Aşağıdaki çıktılar notebook’ta mevcuttur:
  - Loss & Accuracy grafiklerini  
  - Confusion Matrix  
  - Classification Report  

---

## İyileştirme Önerileri
- Epoch sayısı artırılabilir (ör: 10–20 epoch)  
- Learning rate ayarlanabilir  
- Daha karmaşık CNN veya transfer learning (VGG16, ResNet) denenebilir  

---

##  Linkler
-  [Kaggle Notebook](https://www.kaggle.com/code/sudesagmen/notebook103309ba67)  
-  [GitHub Repo](https://github.com/snnmm/cnn-bootcamp)  
