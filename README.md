# Global_AI_Hub_Akbank_ML_Bootcamp_Boston_Housing

**--Turkish--**
# **Boston Housing Veri Seti Analizi ve Makine Öğrenmesi Projesi Raporu**

Bu rapor, bir makine öğrenimi ve veri analizi uzmanı olarak gerçekleştirdiğim Boston Housing veri seti üzerindeki analiz ve modelleme çalışmasını detaylandırmaktadır.

**1. Veri Keşfi ve Ön İşleme (Data Exploration and Preprocessing)**
Veri setini inceleyerek temel istatistikler, veri tipleri ve eksik değerler hakkında bilgi edindik.
Korelasyon matrisi kullanarak özellikler arasındaki ilişkileri inceledik.
Verileri ölçeklendirme ve eğitim-test setlerine bölme işlemlerini gerçekleştirdik.

**2. Model Seçimi**
Farklı model türlerini (Linear Regression, KNeighborsRegressor, RandomForestRegressor) ve ölçeklendirme yöntemlerini (StandardScaler, QuantileTransformer, OneHotEncoder) deneyerek performanslarını karşılaştırdık.
RandomForestRegressor modelinin en iyi performansı gösterdiğini belirledik. Bu modelin hem doğrusal olmayan ilişkileri yakalayabilmesi hem de özellikler arasındaki etkileşimleri ele alabilmesi nedeniyle tercih edildiğini düşünüyoruz.

**3. Model Eğitimi ve Değerlendirme**
Eğitim seti üzerinde RandomForestRegressor modelini eğittik.
Test seti üzerinde modelin performansını değerlendirdik. Modelin tahminlerinin gerçek değerlere yakın olduğunu gösteren görsel ve sayısal analizler gerçekleştirdik.
Son olarak, modelin hiperparametrelerini optimize etmek için RandomizedSearchCV yöntemini kullandık. Bu yöntem, belirli bir aralıkta rastgele parametre kombinasyonlarını deneyerek en iyi model parametrelerini bulmamıza olanak sağlar.

**4. Sonuç**
Bu proje, Boston Housing veri seti üzerinde kapsamlı bir veri analizi ve makine öğrenmesi çalışması sunmaktadır. Seçtiğimiz RandomForestRegressor modeli, veri setindeki karmaşık ilişkileri ve etkileşimleri yakalamak için uygun bir seçenek olduğunu kanıtlamıştır. Ayrıca, RandomizedSearchCV gibi hiperparametre optimizasyon yöntemleri kullanarak modelin performansını daha da iyileştirebiliriz.

Bu proje, bir makine öğrenimi uygulayıcısı olarak hem veri analizi ve modelleme becerilerimizi geliştirmemize hem de gerçek dünya problemlerine etkili çözümler üretmemize olanak sağlamıştır.

Teşekkürler Global AI Hub ve Akbank Takımı!




**--English--**
# **Boston Housing Dataset Analysis and Machine Learning Project Report**

This report details the analysis and modeling work conducted on the Boston Housing dataset as a machine learning and data analysis expert.

**1. Data Exploration and Preprocessing**
Explored the dataset to gain insights into basic statistics, data types, and missing values.
Utilized a correlation matrix to examine relationships between features.
Conducted data scaling and split the data into training and test sets.

**2. Model Selection**
Experimented with different model types (Linear Regression, KNeighborsRegressor, RandomForestRegressor) and scaling methods (StandardScaler, QuantileTransformer, OneHotEncoder) to compare their performances.
Identified RandomForestRegressor as the best-performing model. We chose this model for its ability to capture nonlinear relationships and handle interactions between features.

**3. Model Training and Evaluation**
Trained the RandomForestRegressor model on the training set.
Evaluated the model's performance on the test set. Conducted visual and numerical analyses demonstrating that the model's predictions are close to the actual values.
Finally, used RandomizedSearchCV to optimize the model's hyperparameters. This method allows us to find the best model parameters by trying random parameter combinations within a specified range.

**4. Conclusion**
This project presents a comprehensive data analysis and machine learning study on the Boston Housing dataset. The chosen RandomForestRegressor model has proven to be a suitable option for capturing complex relationships and interactions in the dataset. Additionally, using hyperparameter optimization methods like RandomizedSearchCV, we can further improve the model's performance.

This project has enabled us, as machine learning practitioners, to enhance our data analysis and modeling skills and provide effective solutions to real-world problems.

Big thanks to the Global AI Hub and Akbank Team!!!
