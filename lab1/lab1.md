University: ITMO University

Faculty: FICT

Course: IP telephony technology

Year: 2023

Group: K34202

Author: Кудинов Александр Вадимович

Lab: Lab1

Date of create: 05.03.2022

Date of finished:

Тема работы: Базовая настройка ip-телефонов в среде Сisco packet tracer

Цель работы: Изучить рабочую среду Cisco Packet Tracer, ознакомиться с интерфейсами основных устройств, типами кабелей, научиться собирать топологию. Изучить построение сети IP-телефонии с помощью маршрутизатора, коммутатора и IP телефонов Cisco 7960 в среде Packet tracer

Часть 1
Задание 1: Собрать схему соединения
В среде Cisco Packet Tracer была смоделирована сеть следующей конфигурации (Рис. 1).
![image](https://user-images.githubusercontent.com/87965299/222957536-b697c373-b1e0-4e97-a01f-b97582708cbc.png)

Задание 2: Настройка адресов В интерфейсах PC каждому был задан IP-aдрес в пределах 192.168.0.1 - 192.168.0.8 (Рис. 2).
![image](https://user-images.githubusercontent.com/87965299/222950843-a1754b97-09ba-49a4-b8cc-6e3285c1938c.png)</br>
Рисунок 2 – Настройка адресов</br>
После настройки все узлы сети успешно пингуются между собой (Рис. 3,4,5).</br>
![image](https://user-images.githubusercontent.com/87965299/222957579-b005683b-06d1-4565-aaec-f9786b485403.png)</br>
Рисунок 3 – Пинги из узла PC0</br>
![image](https://user-images.githubusercontent.com/87965299/222957620-74c4ad8a-f793-4c52-b24b-e3fd5b8c8419.png)</br>
Рисунок 4 – Пинги из узла PC4</br>
![image](https://user-images.githubusercontent.com/87965299/222957669-015a9077-7e37-41cd-96b5-d88a27230bc3.png)</br>
Рисунок 5 – Пинги из узла PC7</br>

Часть 2 
Задание 1: Создание сети Создана новая сеть (Рис. 6).</br>
![image](https://user-images.githubusercontent.com/87965299/222978245-6f055d0d-dafd-446f-85a6-e9ba308c70f2.png)</br>
Рисунок 6 – Схема сети</br>

Задание 2: Настроить интерфейс роутера Для работы сети требуется задать адресацию для интерфейса роутера, ответственного за данную подсеть (Рис. 7)</br>
![image](https://user-images.githubusercontent.com/87965299/222978292-29efe1ef-644d-4bac-bdd9-83d52b201b9e.png)</br>
Рисунок 7 – Настройка интерфейса роутера</br>

Задание 3: Настройка IP-телефонии Для работы IP-телефоны необходимо подключить к источнику питания (Рис. 8).
![image](https://user-images.githubusercontent.com/87965299/222978319-a07caa42-9306-4657-ae0b-676520051542.png)</br>
Рисунок 8 – Подключение IP-телефона</br>
Далее производится конфигурация роутера. Вначале настраивается dhcp для автоматической раздачи адресов конечным устройствам, а также загружается прошивка для телефонов (Рис. 9).</br>
![image](https://user-images.githubusercontent.com/87965299/222978482-10ac7b2c-bf3f-4a3c-8f75-66a4cea2835b.png)</br>
 Рисунок 9 – Настройка DHCP для ip-телефонии</br>
 Далее задаются стандартные VoIP-параметры, такие как максимальное количество абонентов (Рис. 10).</br>
 ![image](https://user-images.githubusercontent.com/87965299/222978577-de6b5d81-80d0-4acf-bfc0-008bc663311e.png)</br>
 Рисунок 10 – Настройка параметров сети телефонов</br>
 На этом конфигурация роутера закончена. Далее требуется настроить коммутатор. В нём vlan 1 выделяется под VoIP (Рис. 11).</br>
 ![image](https://user-images.githubusercontent.com/87965299/222978696-9068a0b7-d3e0-4913-b3ea-b7d45f3c20e4.png)</br>
 Рисунок 11 – Конфигурация коммутатора</br>
Настройка телефонии завершена. Теперь в консоли роутера при помощи приведённых команд (Рис. 12) можно задать устройствам</br>
![image](https://user-images.githubusercontent.com/87965299/222979371-e321b130-ad02-4903-a68d-1f83970d04a9.png)</br>
Рисунок 12 – Назначение номеров телефонам</br>
После задания номеров произведена успешная прозвонка с одного IP-телефона на другой (Рис. 13).</br>
![image](https://user-images.githubusercontent.com/87965299/222979418-b56f7e6f-1058-4fb1-aeb3-60c998a45bea.png)</br>
Рисунок 13 – Успешное соединение </br>

Вывод: В результате выполнения лаб.работы был освоен базовый функционал Cisco Packet Tracer, а также смоделирована функционирующая VoIP-сеть.




