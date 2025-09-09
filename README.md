# Linear Regression & Regularization Analysis

Bu proje, **6-LinearRegression ödevi** kapsamında yapılmış bir makine öğrenmesi çalışmasıdır.  
Amacımız farklı regresyon tekniklerini kullanarak veri üzerinde tahmin yapmak ve modelleri değerlendirmektir.

## Kullanılan Modeller
- **Linear Regression**  
- **Lasso Regression**  
- **Ridge Regression**  
- **ElasticNet Regression**

## Yapılan Analizler
- Her modelin performansını **cross-validation** ile gözlemledik.  
- Eksik değerler (**missing values**) uygun yöntemlerle dolduruldu:  
  - Sayısal sütunlarda ortalama (**mean**) ile doldurma  
- Kategorik sütunlar **numeric** değerlere encode edildi, böylece modeller tarafından kullanılabilir hale geldi.
