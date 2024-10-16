# Дослідження фільтра Калмана

Не змінені параметри F H Q R P X

Noise Variance Before Filtering: 16.12

Noise Variance After Filtering: 2.90

![Screenshot_1](https://github.com/user-attachments/assets/29c4bc27-4011-47db-84ec-ed8aeea0939a)


Матриця коваріації оцінки P

Початковий параметр P = 1 замінив на P = 0

Noise Variance Before Filtering: 14.61

Noise Variance After Filtering: 2.41

-Через зміни фільтр гфрше(повільніше) адаптується до змін стану та орієнтуєтся більш на вимірюванні. 

-Трішки краща стабільності на початку фільтрації.

![Screenshot_2](https://github.com/user-attachments/assets/3efbe17c-fa7e-4e6b-8e67-13294cdd7507)


Матриця коваріації оцінки P

Початковий параметр P=1 замінив P=100

Noise Variance Before Filtering: 16.17

Noise Variance After Filtering: 2.31

-Після фільтрації результат залишився подібними до стандартного (не зміненого)

-Адаптація відбувається швидше.

![Screenshot_3](https://github.com/user-attachments/assets/1b9d7a7a-fd45-438a-9705-514643b993f5)


Матриця коваріації шуму процесу Q

Початковий параметр Q=1 замінив Q=0

Noise Variance Before Filtering: 14.82

Noise Variance After Filtering: 10.90

-Через зміни фільтр дуже повільно адаптується.

![Screenshot_4](https://github.com/user-attachments/assets/8150f737-3183-41e4-b9f1-a0f4f6da6bb6)


Матриця коваріації шуму процесу Q

Початковий параметр Q=1 замінив Q=100

Noise Variance Before Filtering: 16.64

Noise Variance After Filtering: 14.10

-Фільтр став більш чутливим до вимірювань. 

-Плавність графіку зменшилась.

-Покращилась адаптація до змін.

![Screenshot_5](https://github.com/user-attachments/assets/ddf99190-721b-425e-b8b8-e07bb8318973)


Матриця коваріації шуму вимірювань R

Початковий параметр R=10 замінив R=0

Noise Variance Before Filtering: 15.57

Noise Variance After Filtering: 15.57

-Графік фільтрованих даних став дуже чутливим до кожного нового вимірювання

-Дані майже ідентичні шумним вимірюванням

![Screenshot_6](https://github.com/user-attachments/assets/66212862-dc51-48f3-844e-1e40d94727fc)


Матриця коваріації шуму вимірювань R

Початковий параметр R=10 замінив R=100

Noise Variance Before Filtering: 16.45

Noise Variance After Filtering: 1.80

-Результат фільтрації згладжений

-Менше реагуе на шумні вимірювання

![Screenshot_7](https://github.com/user-attachments/assets/1b4b3075-db4a-4757-9904-95c6bff87827)
