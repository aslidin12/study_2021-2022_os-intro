---
## Front matter
title: "Лабораторная работа 11"
subtitle: " Программирование в командном процессоре ОС UNIX. Ветвления и циклы."
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

Изучить основы программирования в оболочке ОС UNIX. Научится писать более
сложные командные файлы с использованием логических управляющих конструкций
и циклов.

# Ход работы

Используя команды getopts grep,написал командный файл,который анализирует командную строку,а затем ищет в указанном файле нужные строки.
![Используя команды getopts grep,написал командный файл,который анализирует командную строку,а затем ищет в указанном файле нужные строки.](https://sun9-59.userapi.com/s/v1/if2/6kvJI1OFSEwF6GBlm0rKEejvSRA8_cRq5AoSSWj10M1YLNwJlMCOxDIqVHcBvDspVPms0ZUnH_ptjfuJqf8-S1h9.jpg?size=253x135&quality=96&type=album)

Результат работы скрипта 1.
![Результат работы скрипта 1.](https://sun9-81.userapi.com/s/v1/if2/s1VIoqp_EvVSp-bYrUGla_Ii7vlJcV2fdc2UiTaOVW8Qv6APTpaDCnKgm2p-8YgmkFthBw72e6S8SypxspihyNiS.jpg?size=629x368&quality=96&type=album)

Написал на языке Си программу,которая вводит число и определяет,являетсяли оно
больше нуля,меньше нуля или равно нулю.
![Написал на языке Си программу,которая вводит число и определяет,являетсяли оно
больше нуля,меньше нуля или равно нулю.](https://sun9-74.userapi.com/s/v1/if2/85sv2eyqELkRImkSVQaxnNXDtPhxo5bhipVJkExjQiz6dHsyLmda_VCtOzPEXWLOTLSt5b727Kjjl4EjwtkEfmzX.jpg?size=147x98&quality=96&type=album)

Результат работы скрипта 2.
![Результат работы скрипта 2.](https://sun1-14.userapi.com/s/v1/if2/zoGXe5YSeeulJgvnGjCLL1J8cmZk0ULrzcVf0wzEA1_8nH_DQ-IA4JPMOIwWKQEK1cPoq-D1AnDMqreYsc621lDs.jpg?size=283x133&quality=96&type=album)

Написал командный файл,создающий указанное число файлов, пронумерованных последовательно от 1 до 𝑁.
![Написал командный файл,создающий указанное число файлов, пронумерованных последовательно от 1 до 𝑁.](https://sun1-99.userapi.com/s/v1/if2/kcK93gz4R4bdrEaQAl6PIYDFEWeBG5geY-u5QS3AUnsddzcHMpdmYt9cpDyrYFrH4_g6LMPjCbZeYyrRhRV3Xu-r.jpg?size=346x100&quality=96&type=album)

Результат работы скрипта 3.
![Результат работы скрипта 3.](https://sun9-84.userapi.com/s/v1/if2/cG6lz4wmNAeAvl3T5gH2Nx_YI8zYKOsSXr6-OyKouL6grLjZIg6mDQ0eJqrT9l-301tV4IatTBj3TQwZ3C3z3TYo.jpg?size=506x208&quality=96&type=album)

Написал командный файл,который с помощью команды tar запаковывает в архив все файлы в указанной директории.
![Написал командный файл,который с помощью команды tar запаковывает в архив все файлы в указанной директории.](https://sun1-22.userapi.com/s/v1/if2/WcgNzjdVT3OXm2_LHQJmlCxp9JFa0qNBC6KEpFnXQbiPjrSep4r4OGcXDXIncTf9jmfQEjaM2rY3jZ5cukPr4IY2.jpg?size=388x92&quality=96&type=album)

Результат работы скрипта 3.
![Результат работы скрипта 3.](https://sun9-26.userapi.com/s/v1/if2/apWczcjfb6fvCAMAYbLyBufvoFxtIdTjrPVL8Vcpz0-7PKZubtb-FPiZNTSq121FPFw6zCSjWqJQGltROLjWHBoG.jpg?size=576x164&quality=96&type=album)

Результат работы скрипта 3.
![Результат работы скрипта 3.](https://sun1-95.userapi.com/s/v1/if2/ftnKoQgWe1U0L-fedIwbFLsEspGH-3IigKBDsYqwmBgmZbpbgDLRmQT2c8zKnqMqmrcDpVT3aXDOSJE1W8EvGkLF.jpg?size=508x56&quality=96&type=album)


# Выводы

Изучил основы программирования в оболочке ОС UNIX. Научился писать более
сложные командные файлы с использованием логических управляющих конструкций
и циклов.