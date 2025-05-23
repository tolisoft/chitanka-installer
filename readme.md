# Автоматичен инсталатор за огледало на „Моята библиотека“ за Debian 12

Текущата версия на инсталатора е оптимизирана за работа с актуалното издание на Debian GNU/Linux:

**bookworm**

Файловете в хранилището имат следното предназначение:

 - [chitanka.sh](https://github.com/chitanka/chitanka-installer/blob/master/chitanka.sh "chitanka.sh") – скрипт за инсталация (и не само) на уеб сървър, автоматична настройка на виртуален хост и сваляне на съдържанието на софтуера, който задвижва „Моята библиотека“. Скриптът има функционалност за добавяне на отложена задача за автоматично обновяване на огледалото.
 - [nginx-vhost.conf](https://github.com/chitanka/chitanka-installer/blob/master/nginx-vhost.conf "nginx-vhost.conf") – виртуален хост за уеб сървъра Nginx, оптимизиран за огледалото.
 - [parameters.yml](https://github.com/chitanka/chitanka-installer/blob/master/parameters.yml "parameters.yml") – кофнигурационен файл за софтуера на „Моята библиотека“ 

Инсталаторът е изпробван на на Debian Bookworm.

Препоръчително е да се използва от потребители с натрупан опит в управлението и работата с GNU/Linux и дистрибуции базирани на Debian.

Актуалната версия на инсталатора е 1.2, като тя е изпробвана и преминала тестове върху следните дистрибуции:

**Debian**:
- 12 (bookworm)

