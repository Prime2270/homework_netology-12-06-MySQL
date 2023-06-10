# Домашнее задание к занятию "`Репликация и масштабирование. Часть 1`" - `Яковлев Константин`


### Задание 1 На лекции рассматривались режимы репликации master-slave, master-master, опишите их различия. Ответить в свободной форме.

```
- репликация master-slave такой вид репликации позволяет распределить нагрузку базы данных
на несколько серверов, на которых и будут работать реплики. Чиать данные следует с реплик.

- репликация master-master явдяется не жалательной настройкой, т.к. 
при разрыве соединения восстановить работу приложения будет очень проблематично.
Это связанно с тем что между нодами может возникнуть "спор",
на какой из нод данные будут более актуальны.
```

### Задание 2 Выполните конфигурацию master-slave репликации, примером можно пользоваться из лекции.

![job2](https://github.com/Prime2270/homework_netology-12-06-MySQL/blob/main/screenshots/job2.png)

![job2(status)](https://github.com/Prime2270/homework_netology-12-06-MySQL/blob/main/screenshots/job2%20(status).png)

![job2(master)](https://github.com/Prime2270/homework_netology-12-06-MySQL/blob/main/screenshots/job2%20(master).png)

![job2(slave)](https://github.com/Prime2270/homework_netology-12-06-MySQL/blob/main/screenshots/job2%20(slave).png)
