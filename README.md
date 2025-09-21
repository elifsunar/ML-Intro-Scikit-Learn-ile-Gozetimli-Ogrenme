##  Makine Öğrenimine Giriş – Scikit-Learn ile Gözetimli Öğrenme Uygulamaları

Bu çalışma, **Scikit-Learn** kütüphanesini kullanarak temel gözetimli öğrenme (supervised learning) tekniklerini adım adım tanıtan bir Jupyter Notebook içeriğidir. Veri yüklemeden model değerlendirmesine kadar olan temel kavramları hem teorik hem de uygulamalı örneklerle ele alır.

---

### İçerik Özeti
- **Scikit-Learn ve Temel Kütüphaneler**  
  NumPy, Pandas, Matplotlib ve mglearn gibi makine öğrenimi projelerinde sıkça kullanılan Python kütüphanelerinin kısa tanıtımı.

- **Iris Veri Seti ile k-Nearest Neighbors (k-NN)**  
  - Iris çiçeği türlerini sınıflandırmak için gözetimli öğrenme örneği  
  - Eğitim ve test verisine ayırma, `train_test_split`  
  - k-NN algoritmasının çalışma mantığı ve model doğruluk değerlendirmesi

- **Wisconsin Meme Kanseri Veri Seti**  
  - KNeighborsClassifier ile farklı `n_neighbors` değerlerinin model performansına etkisi  
  - Aşırı/eksik öğrenme (overfitting & underfitting) kavramlarının görselleştirilmesi

- **Doğrusal Modeller (Linear Models)**  
  - **Logistic Regression** ve **Linear SVM (LinearSVC)** ile sınıflandırma  
  - Düzenlileştirme (regularization) parametresi C’nin model karmaşıklığına etkisi

- **Naive Bayes Sınıflandırıcıları**  
  - GaussianNB, BernoulliNB ve MultinomialNB modellerinin temel prensipleri ve kullanım alanları

- **Karar Ağaçları (Decision Trees)**  
  - Pre-pruning stratejileri (max_depth, max_leaf_nodes, min_samples_split)  
  - Özellik önem derecesi (feature importance) analizi ve görselleştirme

---

### 📚 Kaynaklar
- [Scikit-learn Documentation](https://scikit-learn.org/stable/index.html)
- [Scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
- *Introduction to Machine Learning with Python* – Andreas C. Müller & Sarah Guido
