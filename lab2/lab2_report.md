University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [IP-telephony](https://itmo-ict-faculty.github.io/ip-telephony/)
Year: 2022/2023
Group: K34212
Author: Leshkov Roman Sergeevich
Lab: Lab2
Date of create: 17.03.2023
Date of finished: 17.03.2023

Цель работы: 

Изучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.

Ход работы:

Часть 1

Собрана схема соединения из одного роутера, свича L3 и трех ip-телефонов. Роутер и свич соединены кроссовым проводом.

![Alt text](screens/Screenshot_1.jpg)

Роутеру назначено имя CMERouter командой.

    hostname CMERouter

![Alt text](screens/Screenshot_2.jpg)

Отключен синтаксис ввода слов от DNS серверов, что поможет избежать блокировки ввода при вводе неправильной команды.

    no ip domain-lookup

![Alt text](screens/Screenshot_4.jpg)

Создан логин и пароль для защиты роутера в удаленном режиме и в режиме консоли.

    username rlesh priv 15 

![Alt text](screens/Screenshot_5.jpg)
![Alt text](screens/Screenshot_6.jpg)
![Alt text](screens/Screenshot_7.jpg)
![Alt text](screens/Screenshot_8.jpg)
![Alt text](screens/Screenshot_9.jpg)
![Alt text](screens/Screenshot_10.jpg)
![Alt text](screens/Screenshot_11.jpg)
![Alt text](screens/Screenshot_12.jpg)

Часть 2

![Alt text](screens/Screenshot_13.jpg)
![Alt text](screens/Screenshot_14.jpg)
![Alt text](screens/Screenshot_15.jpg)
![Alt text](screens/Screenshot_16.jpg)

Вывод:
