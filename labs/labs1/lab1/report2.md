---
## Front matter
title: "Лабораторная работа 2"
subtitle: "Управления версиями"
author: "Аслиддин Ахлиддинзода"

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

Изучить идеологию и применение средств  контоля версий. 
Освоить умения по работе с git.

# Ход работы

Создайте учетную запись на github.com.
Заполните основные данные.
Скачивание и установка git-flow.

![Скачивание и выдача прав на выполнение](https://github.com/aslidin12/study_2021-2022_os-intro/blob/master/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BB%D0%B0%D0%B1%D1%8B%202.pdf) 

![Базовая настройка git](https://github.com/aslidin12/study_2021-2022_os-intro/blob/master/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BB%D0%B0%D0%B1%D1%8B%202.pdf)

![Создаем ключи PGP и SSG](https://github.com/aslidin12/study_2021-2022_os-intro/blob/master/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BB%D0%B0%D0%B1%D1%8B%202.pdf)

![Добавление ключа  PGP в Github](https://github.com/aslidin12/study_2021-2022_os-intro/blob/master/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BB%D0%B0%D0%B1%D1%8B%202.pdf)

![Мой сгенерированный PGP ключ](https://github.com/aslidin12/study_2021-2022_os-intro/blob/master/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BB%D0%B0%D0%B1%D1%8B%202.pdf)

![Вставил полученный ключ в полу ввода в github](https://github.com/aslidin12/study_2021-2022_os-intro/blob/master/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BB%D0%B0%D0%B1%D1%8B%202.pdf)

![Настроойка автоматических подписей коммитов git](https://github.com/aslidin12/study_2021-2022_os-intro/blob/master/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%BB%D0%B0%D0%B1%D1%8B%202.pdf)

# Выводы

Изучил идеологию и применил средтва контроля версий.
Освоил умения по работе с git.
