---
## Front matter
title: "Лабораторная работа 1"
subtitle: "Именованные каналы."
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

Приобретение практических навыков работы с именованными каналами.

# Ход работы

В домашнем каталоге создал необходимые файлы.
![В домашнем каталоге создал необходимые файлы.](https://sun9-56.userapi.com/s/v1/if2/RRDdMM0-9qGfSkWuG1um-HPHXaVs3bAjh1sRTC7i-XSertVqDWP6xrlLvJlgjqE1g2whpSIGHfiak2swBxyO5sE3.jpg?size=368x63&quality=96&type=album)

Заполнил common.h.
![Заполнил common.h.](https://sun9-70.userapi.com/s/v1/if2/TjCEatGku2ZFpvkz7Y26jO9uZXmQByBjXmIKjM6lDgDCuyJOYpn5PRnBRa0ZuoRwSvbMl1j3mNvwVoot6nUMRWEb.jpg?size=167x220&quality=96&type=album)

Заполнил server.c.
![calculate.h](https://sun9-74.userapi.com/s/v1/if2/yEBitZPvUTGyw28e5lusHuzSZlm9F9R-4QLBU6DdISISB2zLyUXaO_OARvExWiWWf5BCfBcVaV5yRYQVh0yE8KLW.jpg?size=330x182&quality=96&type=album)

Заполнил client.c.
![calculate.c](https://sun1-16.userapi.com/s/v1/if2/0CTaZm48i-lrkSuNooS4PXLVkzhbbnfrZJf9tIS_qkYtU8plp8zeYMr4r5t47ANk6WgmLg-IOErCWsokuDBjpUq3.jpg?size=326x192&quality=96&type=album)

Создал Makefile.
![Создал Makefile.](https://sun9-58.userapi.com/s/v1/if2/Am_uXKuCM0xOtszB-0BQGD7pd3p10n0FrSdQ-WBaI9w7oLpAc6j7Py41mPbkPtT9YJYLkCbFc9oUph2T2UQaHEEx.jpg?size=274x33&quality=96&type=album)

Заполнил Makefile.
![Заполнил Makefile.](https://sun9-18.userapi.com/s/v1/if2/5H0m8bsL_y119gh3dAM8sh5McQtz9EIGcYqLyAjA0EfeRzCAo5YarX1_9WtDmNaeXR3NfHgNJOZUgLM8Aa1D93lf.jpg?size=149x131&quality=96&type=album)

# Выводы

Приобрел практических навыков работы с именованными каналами.