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

Eng yaxshi algorithm : Random Forest

Baholash -> RMSE : 3177.4411557321496

2-model air-customer-churn

Aviakompaniya yo'lovchilarining qoniqishini bashorat qilish

Dataset(Ushbu maʼlumotlar toʻplami) aviakompaniya yoʻlovchilarining qoniqish soʻrovini oʻz ichiga oladi.

Eng yaxshi natija Random Forest algaritmida Cross-Validation-Score : 98.89995238364142
