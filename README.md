# Astım Hastalığı Tahmini
Bu proje, astım hastalığını tahmin etmek için bir makine öğrenimi modeli geliştirmeyi amaçlamaktadır. Model, karar ağaçları algoritmasını kullanarak astım semptomlarını ve demografik bilgileri analiz ederek hastalığın varlığını tahmin etmektedir.

## Veri Seti
Veri seti, Kaggle üzerinde Deepayan Thakur tarafından sağlanmıştır ve astım hastalığını tahmin etmeye yönelik çeşitli özellikler içermektedir. Veri setine buradan ulaşabilirsiniz.

## Kullanılan Özellikler
- Tiredness
- Dry-Cough
- Difficulty-in-Breathing
- Sore-Throat
- None_Sympton
- Pains
- Nasal-Congestion
- Runny-Nose
- None_Experiencing
- Age_0-9
- Age_10-19
- Age_20-24
- Age_25-59
- Age_60+
- Gender_Female
- Gender_Male
- Severity_Mild
- Severity_Moderate
- Severity_None
- Hedef Değişken

Difficulty-in-Breathing: Bu sütun, astım hastalığı tahmini için hedef değişken olarak kullanılmıştır.

## Kullanılan Model ve Yöntemler
Karar Ağaçları (Decision Trees)
Karar ağaçları, veri setindeki örnekleri belirli özelliklere göre dallara ayırarak sınıflandırma yapmayı sağlar. Bu projede, astım hastalığını tahmin etmek için karar ağaçları algoritması kullanılmıştır.

## Model Eğitimi ve Değerlendirme
Model, veri setindeki özellikler ve hedef değişken kullanılarak eğitilmiştir. Modelin performansı, doğruluk (accuracy) ve sınıflandırma raporu (classification report) ile değerlendirilmiştir.

- Doğruluk (Accuracy): %64.14
- Sınıflandırma Raporu:
- Precision:
- No Difficulty: 0.63
- Difficulty: 0.65
- Recall:
- No Difficulty: 0.68
- Difficulty: 0.60
- F1-Score:
- No Difficulty: 0.65
- Difficulty: 0.63
- Hata Matrisi
- Modelin performansını daha iyi anlamak için hata matrisi kullanılmıştır. Bu, modelin hangi sınıflarda daha doğru tahminler yaptığını ve hangi sınıflarda hatalar yaptığını gösterir.

## Teknolojiler
Bu projede kullanılan başlıca teknolojiler ve kütüphaneler şunlardır:

- Python
- Pandas (veri işleme)
- Scikit-learn (makine öğrenimi modelleri ve değerlendirme metrikleri)
- Matplotlib (veri görselleştirme)
- Gelecek Çalışmalar
- Bu proje, astım hastalığını tahmin etmek için temel bir model sunmaktadır. Gelecekteki çalışmalar şunları içerebilir:

## Açıklanabilirlik:

Diğer makine öğrenimi algoritmalarını (Random Forest, Gradient Boosting, vb.) deneyerek modelin performansını artırma.
Daha fazla veri ve özellik kullanarak modelin doğruluğunu artırma.
Modelin açıklanabilirliğini artırmak için SHAP (SHapley Additive exPlanations) ve LIME (Local Interpretable Model-agnostic Explanations) gibi açıklanabilirlik araçlarını kullanma.
Gerçek dünyada kullanılabilir bir uygulama veya web arayüzü geliştirme.

## İletişim
Bu proje hakkında herhangi bir sorunuz veya geri bildiriminiz varsa, lütfen benimle iletişime geçmekten çekinmeyin.

## Lisans

Çalışmanın lisans haklaı İbrahim Püsküülü adına saklıdır. Ve çalışma 2024 yılında yapılmıştır. Lisans hakkı için iletişime geçebilirsiniz.
