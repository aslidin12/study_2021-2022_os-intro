---
## Front matter
title: "Лабораторная работа 7"
subtitle: " Командная оболочка Midnight Commander"
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

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Ход работы

Создал текстовой файл text.txt.
![Создал текстовой файл text.txt.](https://sun9-24.userapi.com/s/v1/if2/bVCW_AzlfbPazrfptl19egd1KgaKcDtKHfd49QAw9YJEf2lcREoNoxJ1Sa-ez-dc0vlSL7Vt4tYu27GExLdC0K-a.jpg?size=269x95&quality=96&type=album)

Открыл этот файл с помощью встроенного в mc редактора
![Открыл этот файл с помощью встроенного в mc редактора](https://sun9-72.userapi.com/s/v1/if2/ny_N50G7OjZqQzWgqJy6XfHbshISXYmll83UKd-GT2dsvIiaqAuUVhvqihdAjot5Zr5-WbQp5JR03vNUlJ1lcfJA.jpg?size=449x49&quality=96&type=album)

Вставил в открытый файл небольшой фрагменттекста,скопированный из Интернета
![Вставил в открытый файл небольшой фрагменттекста,скопированный из Интернета](https://sun9-31.userapi.com/s/v1/if2/Tlc_mr8q0TcXB1v5Am6lYX3lohaAp160Onxa366Lqrc8loRMVxLqStasmzmXMRKwA9vt4Itp9PxthVF_lfUiKWVb.jpg?size=553x66&quality=96&type=album)

Удалил строку текста
![Удалил строку текста](https://sun9-61.userapi.com/s/v1/if2/QIrGtbDwAKL5xpqMKPZjj8V4Qt5bcxLuMhWclaFlXzWfgKZC-OdOGMh7RJyHhW4rHw5dFwdotGjrB-SjnGSH_4F4.jpg?size=554x118&quality=96&type=album)

Выделил фрагменттекста и перенес его на новую строку..
![Выделил фрагменттекста и перенес его на новую строку.](https://sun9-48.userapi.com/s/v1/if2/yEjHUhivkRoKXcTrn0WOzlCAgTKvuTCFme82qWdVMy-mb-v0bcYg2lsUVOAcnJQ-z_ye_X7swsoAsnT2PgEmxZnE.jpg?size=508x75&quality=96&type=album)

Перешел в конец и в начало файла (нажав комбинацию клавиш) и написал некоторый текст. 
![Перешел в конец и в начало файла (нажав комбинацию клавиш) и написал некоторый текст.](https://sun9-48.userapi.com/s/v1/if2/z4F3NnBfyNKOwu1aNq3sejrvYQjuh_cLCphpAgiR04ClMxgH6nUjA8aCgQFK_33yguWAZC7SJsiOms-9lEmaMaix.jpg?size=509x90&quality=96&type=album)

Сохранил и закрыл файл.
![Сохранил и закрыл файл.](https://sun9-84.userapi.com/s/v1/if2/n2b8NVpiqpRkaLstISMCvd4E6l7TYgnMF5KhvVhfze4Hfj-_j-sxrymB28STnvmgoFsfjI0jVUqset893j7oQg4N.jpg?size=510x169&quality=96&type=album)

Открыл файл с исходным текстом и ,используя меню редактора,включил подсветку синтаксиса.
![Открыл файл с исходным текстом и ,используя меню редактора,включил подсветку синтаксиса.](https://sun9-51.userapi.com/s/v1/if2/OdHs4vr0N2VFYSPq-fWgmf8PUuZ0eamIUiLlVJpu1ssy5X7nBoizF5QH_gVsSlFvpHZ__oRo1kQxSsN9AeiEVwR8.jpg?size=500x266&quality=96&type=album)

Выключил подсветку.
![Выключил подсветку.](https://sun9-12.userapi.com/s/v1/if2/jgSMegOeFLp-J57MJxErFv4w1lB2Vn5UU1PTZtCHK5Gc9Bg_EfxkSLBLbLVDz3EyM1TqQLc8vmmONNVGPhSf0x7N.jpg?size=506x269&quality=96&type=album)

# Выводы

Освоил основные возможности командной оболочки Midnight Commander. Приобрел навыки практической работы по просмотру каталогов и файлов; манипуляций с ними.
