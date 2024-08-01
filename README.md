# project-models

### Pnevmaniya tashxisi 

Pnevmaniya bor yoki yo'qligini aniqlovchi dastur

dataset: Rasm ko'rinishida.

<div align="left">
  <img height="400" src="https://github.com/Philomath2020/project-models/blob/main/pic/p1%20.png"  />
</div>

Model Train:

vision_learner(dls, resnet34, metrics=accuracy)

<div align="left">
  <img height="200" src="https://github.com/Philomath2020/project-models/blob/main/pic/pt2.png"  />
</div>

Baholash: Confusion matrix:

<div align="center">
  <img height="400" src="https://github.com/Philomath2020/project-models/blob/main/pic/pc3.png"  />
</div>

Classification Report:

Accuracy: 98 %

<div align="left">
  <img height="300" src="https://github.com/Philomath2020/project-models/blob/main/pic/pc4.png"  />
</div>

### airticket-price-prediction model

Dataset (Ushbu maʼlumotlar toʻplami) Hindistondagi aviaqatnovlar orqali yig'ilgan 

Vazifa : Avia Chiptalar narxini predict qilish

Tarkib:

1. ID: Ketma - ketlik uchun qo'yilgan sonlar.
2. Airline: Parvoz qilingan aviakompaniya nomi.
3. Flight: Parvoz qilingan ID raqami.
4. Source_city: Parvoz qaysi shahardan boshlanishi.
5. Departure_time: Samolyotning ketish vaqti.
6. Stop: Parvoz davomida to'xtashlar soni.
7. Arrival_time: Qaytish vaqti.
8. Destination_city: Qaysi davlatga parvoz qilinayotgani.
9. Class: Foydalanuvchi samolyotning qaysi klass turidan foydalanib uchganligi.
10. Duration: Parvoz davomiyligi.
11. Days_left: Samolyotning qancha vaqtdan keyin qaytishi.

Grafik:

<div align="center">
  <img height="400" src="https://github.com/Philomath2020/project-models/blob/main/pic/ag2.png"  />
</div>

Eng yaxshi algorithm : Random Forest

Baholash -> RMSE : 3177.4411557321496

### air-customer-churn

Aviakompaniya yo'lovchilarining qoniqishini bashorat qilish

Dataset(Ushbu maʼlumotlar toʻplami) aviakompaniya yoʻlovchilarining qoniqish soʻrovini oʻz ichiga oladi.

Confusion Matrix to'gri va xatolar sonini ko'rish:

<div align="center">
  <img height="300" src="https://github.com/Philomath2020/project-models/blob/main/pic/ac5.png"  />
</div>

Eng yaxshi natija Random Forest algaritmida Cross-Validation-Score : 98.89995238364142

Accuracy:
<div align="left">
  <img height="300" src="https://github.com/Philomath2020/project-models/blob/main/pic/acs6.png"  />
</div>

### Toshkent shahrida uylarning narxini aniqlash.

Dataset tarkibi:

location - sotilayotgan uy manzili
district - uy joylashgan tuman
rooms - xonalar soni
size - uy maydoni (kv.m)
level - uy joylashgan qavat
max_levels - ja'mi qavatlar soni
price - uy narxi

Algoritm: RandomForestRegressor

Result : Root_mean_squared_error: 5% atrofida


### Loan status prediction Nasiyaga berish bermaslik

Dataset :

<div align="left">
  <img height="200" src="https://github.com/Philomath2020/project-models/blob/main/pic/l1.png"  />
</div>

Support Vector Machine model -> Training

Accuracy data score fl 0.8333333333333334

<div align="left">
  <img height="100" src="https://github.com/Philomath2020/project-models/blob/main/pic/l2.png"  />
</div>

### Diabet prediction

Diabet bor yoki yo'qligini aniqlovchi dastur

dataset:

<div align="left">
  <img height="300" src="https://github.com/Philomath2020/project-models/blob/main/pic/d1.png"  />
</div>

Baholash: Confusion matrix

<div align="center">
  <img height="400" src="https://github.com/Philomath2020/project-models/blob/main/pic/d2.png"  />
</div>

Classification Report:

<div align="left">
  <img height="400" src="https://github.com/Philomath2020/project-models/blob/main/pic/d3.png"  />
</div>

DecisionTrees's Accuracy:  0.8311688311688312

### Mijozning noroziligini (customer churn) aniqlash dasturi

Dataset:

<div align="left">
  <img height="200" src="https://github.com/Philomath2020/project-models/blob/main/pic/c1.png"  />
</div>

Statistics: Qolgan va ketgan mijozlar nisbati pie charm:

<div align="left">
  <img height="400" src="https://github.com/Philomath2020/project-models/blob/main/pic/c2.png"  />
</div>

Qolgan va qaytgan mijozlar jinsi , oilaliligi:

<div align="left">
  <img height="300" src="https://github.com/Philomath2020/project-models/blob/main/pic/c3.png"  />
</div>

Model traning : XGBoostClassifier

Baholash : Classification Report

<div align="left">
  <img height="300" src="https://github.com/Philomath2020/project-models/blob/main/pic/c4.png"  />
</div>

Model aniqligi: 0.941699604743083

Confusion Matrix:

<div align="center">
  <img height="400" src="https://github.com/Philomath2020/project-models/blob/main/pic/c5.png"  />
</div>
