---
## Front matter
title: "Лабораторная работа 10"
subtitle: " Программирование в командном процессоре ОС UNIX. Командные файлы."
author: "Аслиддин Ахлиддинзода"
НФИ бд 01-21
## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать
небольшие командные файлы.

# Ход работы

Написал скрипт,который при запуске будет делать резервную копию самого себя в другую директорию backup в вашем домашнем каталоге. При этом файл архивируется в tar.
![Написал скрипт,который при запуске будет делать резервную копию самого себя в другую директорию backup в вашем домашнем каталоге. При этом файл архивируется в tar.](https://sun9-3.userapi.com/s/v1/if2/3XF6j29cJKX05L_qJ9Hk0m2-1fs1Tv8TgCZWWKmOC88coyu4nSKHkqUYV30lwTS02Ml02JBiT3cx9ZGqaCexqPBf.jpg?size=408x37&quality=96&type=album)

Результат работы скрипта 1.
![Результат работы скрипта 1.](https://sun9-21.userapi.com/s/v1/if2/Fr52d4_PfMFilNWYdk4by6CW8zcAZWmTl6CUMGUdLxktg3hAMIPQnUmwfxxcnfvwccgOuCvmmGSC3xI2tWDekDzq.jpg?size=423x178&quality=96&type=album)

Написал пример командного файла,обрабатывающего любое произвольное число аргументов командной строки, в том числе превышающее десять.
![Написал пример командного файла,обрабатывающего любое произвольное число аргументов командной строки, в том числе превышающее десять.](https://sun9-16.userapi.com/s/v1/if2/N2-ff9o9TYALXNxF8hoKfw7i8Ay9Zv99y5k-hZpbjiuEEf3RijP4XS_umezM_fuufD4nSCNpxgih9VDYb52LdFLC.jpg?size=126x76&quality=96&type=album)

Результат работы скрипта 2.
![Результат работы скрипта 2.](https://sun9-85.userapi.com/s/v1/if2/GMmEl0KkFPxNT6jvlG1_bZJfkgtk1T6TRh5HshkkRNgrPqMaXnsDDtbbJJHZnzv2ZKliiFHo2dpV8k2BtB0amNSs.jpg?size=371x169&quality=96&type=album)

Написал командный файл—аналог команды ls. Требовалось,чтобы он выдавал информацию о нужном каталоге и выводил информацию о возможностях доступа к файлам этого каталога. 
![Написал командный файл—аналог команды ls. Требовалось,чтобы он выдавал информацию о нужном каталоге и выводил информацию о возможностях доступа к файлам этого каталога.](https://sun9-81.userapi.com/s/v1/if2/QsMjlvI3t6h-Y0g97trGD3Dryr5lOCwoJ1BBp16tneyX5rzBOVZK3OiG9DFL8gzDuICXDNkYxqbIwJCkKyK5dnWH.jpg?size=281x135&quality=96&type=album)

Результат работы скрипта 3.
![Результат работы скрипта 3.](https://sun9-78.userapi.com/s/v1/if2/weme44H5Q5Qh0hd_v4gjWZbLIFN-XoPVwsIaW2zUqIH8tiC5UT0-2z4nkKdFHwKMYs9jZRKyn9KnE4yLmwQQOYry.jpg?size=292x120&quality=96&type=album)

Написал командный файл,который получает в качестве аргумента командной строки формат файла и вычисляет количество таких файлов в указанной директории.Путь к директории также передаётся в виде аргумента командной строки.
![Написал командный файл,который получает в качестве аргумента командной строки формат файла и вычисляет количество таких файлов в указанной директории.Путь к директории также передаётся в виде аргумента командной строки.](https://sun9-25.userapi.com/s/v1/if2/JbWRyeC9sXn1nOMyCpwjzHvusr4wlY_KDWG0AyE7Wmo72V93aWfme-ejxtZZMmiaYZqXN_2XZwr_wN5SfPSGBWxr.jpg?size=221x61&quality=96&type=album)

Результат работы скрипта 3.
![Результат работы скрипта 3.](https://sun9-84.userapi.com/s/v1/if2/aCE2HQLvBdaK9G15abp7EjsAyO7eBZdeX91v2_PuwvkuViRw2op0unPetJPmcQ4Q5SL51wj5VdguTdJrY2XpMVR8.jpg?size=116x36&quality=96&type=album)

# Выводы

Изучил основы программирования в оболочке ОС UNIX/Linux. Научился писать
небольшие командные файлы..