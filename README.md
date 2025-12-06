# House-Energy-Consumption-Regression
House Energy Consumption Regression

Evlerin günlük enerji tüketimini tahmin eden çok modelli, karşılaştırmalı bir regresyon analizi.

📌 Proje Amacı

Bu çalışmanın hedefi, bir evin günlük enerji tüketimini (kWh) mevcut özelliklere dayanarak tahmin etmek.
Hem Decision Tree Regression modeli üzerinde GridSearchCV ile hiperparametre optimizasyonu yapıp en iyi ayarları buluyoruz,
hem de farklı regresyon modellerini karşılaştırarak hangisinin en iyi R² skorunu verdiğini ortaya koyuyoruz.

📂 Kullanılan Veri

Dataset: 12-house_energy_regression.csv

Hedef değişken: daily_energy_consumption_kwh

Bağımsız değişkenler: ev özellikleri, ortam bilgileri vb. (kolonlara göre değişiyor)

🧪 Kullanılan Modeller

Aşağıdaki tüm regresyon modelleri eğitildi ve R² skorlarına göre karşılaştırıldı:

Linear Regression

Ridge

Lasso

Decision Tree Regressor

Decision Tree + GridSearchCV (optimize edilmiş model)

KNN Regressor

SVR

Gradient Boosting Regressor 

Random Forest 
