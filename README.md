# goit-de-fp

## Part 1: Building an End-to-End Streaming Pipeline
![p1_1](https://github.com/user-attachments/assets/3092f1fa-e8a3-4415-99c1-5c77fd9118cd)
На цьому скріншоті відображено результат запису у таблицю <b>enriched_athlete_avg</b>  

![p1_2](https://github.com/user-attachments/assets/b6b6d755-9524-4d6e-a580-1f0db643d6fa)  
Скріншот підтверджує запис даних у kafka-топік <b>artur_home_enriched_athlete_avg</b>  

Дані та часові мітки на двох скріншотах співпадають, що відповідає умовам виконання задачі
  
## Part 2: Building an End-to-End Batch Data Lake
![p2_1](https://github.com/user-attachments/assets/6ea6e7e5-a6cf-4f1a-a164-0c7b2314fb85)
Результат відображення збережених даних в таблиці <b>bronze/athlete_event_results</b>
  
![p2_2](https://github.com/user-attachments/assets/2596bbb7-fa1a-4f47-bcce-9b95a21beff4)  
Результат відображення збережених даних в таблиці <b>silver/athlete_event_results</b>
  
![p2_3](https://github.com/user-attachments/assets/8257ffe2-9d14-4a81-8b8f-b94dae7479e4)    
Результат відображення збережених даних в таблиці <b>gold/avg_stats</b>  
  
![p2_4](https://github.com/user-attachments/assets/97933219-bb47-46d8-b701-25c69469d8b2)  
У цьому скріншоті відображено DAG з трьома успішно відпрацьованими батчами
