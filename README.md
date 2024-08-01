# project-models

1-model airticket-price-prediction model

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

<div align="center">
  <img height="300" src="https://github.com/Philomath2020/project-models/blob/main/pic/ag2.png"  />
</div>

Eng yaxshi algorithm : Random Forest

Baholash -> RMSE : 3177.4411557321496

2-model air-customer-churn

Aviakompaniya yo'lovchilarining qoniqishini bashorat qilish

Dataset(Ushbu maʼlumotlar toʻplami) aviakompaniya yoʻlovchilarining qoniqish soʻrovini oʻz ichiga oladi.

Confusion Matrix to'gri va xatolar sonini ko'rish:

<div align="center">
  <img height="200" src="https://github.com/Philomath2020/project-models/blob/main/pic/ac5.png"  />
</div>

Eng yaxshi natija Random Forest algaritmida Cross-Validation-Score : 98.89995238364142

<div align="center">
  <img height="300" src="https://github.com/Philomath2020/project-models/blob/main/pic/acs6.png"  />
</div>

3 - model Toshkent shahrida uylarning narxini aniqlash.

4 - model Loan status prediction Nasiyaga berish bermaslik

Support Vector Machine model -> Training

Accuracy data score fl 0.8333333333333334

5 - model Diabet prediction

DecisionTrees's Accuracy:  0.8311688311688312

6 - model Mijozning noroziligini (customer churn) aniqlash

Model traning : XGBoostClassifier

Model aniqligi: 0.941699604743083
