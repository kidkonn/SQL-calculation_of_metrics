## SQL-запрос для расчета и вывода метрик
Образовательная платформа, образовательные курсы которой состоят из различных уроков, каждый из которых состоит из нескольких маленьких заданий. Каждое такое маленькое задание называется "горошиной".

Образовательная платформа предлагает пройти студентам курсы по модели trial: студент может решить бесплатно лишь 30 горошин в день. Для неограниченного количества заданий в определенной дисциплине студенту необходимо приобрести полный доступ. Команда провела эксперимент, где был протестирован новый экран оплаты.

Задача:

Посчитать и вывести:
* ARPU, 
* ARPAU, 
* CR в покупку, 
* СR активного пользователя в покупку, 
* CR активного пользователя по математике в покупку по математике

**Активным** считается пользователь, за все время решивший больше 10 задач правильно в любых дисциплинах.

**Активным по математике** считается пользователь, за все время решивший 2 или больше задач правильно по математике.

Результат представлен в `SQL_metrics.ipynb`
