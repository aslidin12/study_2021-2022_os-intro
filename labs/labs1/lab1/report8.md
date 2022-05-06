---
## Front matter
title: "Лабораторная работа 8"
subtitle: " Текстовый редактор vi"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi.

# Ход работы

Создал каталог с именем lab08 и перешел в него.
![Создал каталог с именем lab08 и перешел в него.](https://sun9-83.userapi.com/s/v1/if2/eGQwQw3Lnol1LHg7D4dNr6kS3aX6AT75ezDP9IFvd8rA_KNoF6o1kZbeT-pz87RYffGTSL8BEmBSdZfhrsq-uoEZ.jpg?size=369x224&quality=96&type=album)

Вызвал vi  с создал файл hello.sh
![Вызвал vi  с создал файл hello.sh](https://sun9-52.userapi.com/s/v1/if2/hohalfVtbuAck9UPEBXN-UHKo3EOZ5vmTQUJlRh7iVoMLON9HaAlmIi5FIOvB8uSauPLqxewhu7WXcODvG64mUbj.jpg?size=276x15&quality=96&type=album)

Ввел текст.
![Ввел текст.](https://sun9-64.userapi.com/s/v1/if2/TEiF67hLjSQezmYeHEpCQsIpeDs0XjmhEb0hbvF6_Y_6Aey-N-irj6AB17Utw3EtpEvYO5ilVvMdImUbziQwit3M.jpg?size=116x287&quality=96&type=album)

Сохранил и вышел. Сделал файл испольняемым.
![Сохранил и вышел. Сделал файл испольняемым.](https://sun9-53.userapi.com/s/v1/if2/CNlnkAz23KQKKDcUNQymEnC5-y0cEcs3NJChT2xcGG3gzrl4P0ziLorFn_AdXK_vTQYXaIwoKt2ZcJRSWVuUk3jH.jpg?size=297x25&quality=96&type=album)

Установимл курсор во вторую строку и изменил HELL на HELLO.
![Установимл курсор во вторую строку и изменил HELL на HELLO.](https://sun9-35.userapi.com/s/v1/if2/raAdxBRl7fJRlnC4-sjaB1-OsGsJBamaiLbpkwX4scwoEmdsiWwTkrFXfaJATK-evCuGO96QzfAQmwifURa2aUgt.jpg?size=110x99&quality=96&type=album)

Стер LOCAL и написал вместо него local. 
![Стер LOCAL и написал вместо него local.](https://sun9-6.userapi.com/s/v1/if2/6cIihyCT0A_ZjwJwkF8zSixMmTdZm1bfgHWHkKliyOjeIvgPhYEZsuQ6_JOaTpZif9FQtxEJOHU66sPVqjWCfuOP.jpg?size=108x96&quality=96&type=album)

Вставил в последнюю строку:echo &HELLO.
![Вставил в последнюю строку:echo &HELLO.](https://sun9-46.userapi.com/s/v1/if2/KOVabl8oyf0wjvhj7J0lsD9QFQzlzyPTKOLwThUzyabDEm0iy3qO6wO3KU5rIfc7vLMoOFNVDvc33bPGJHzdOI3v.jpg?size=114x101&quality=96&type=album)

Удалил его.
![Удалил его.](https://sun9-2.userapi.com/s/v1/if2/gbjA0JCgOckxeDXB6UqbjzYM1M8I9Z2NXRHzI4f9qniEcxdFdUkJKzWTD4Lhbzd56kf2DfVQNvIrgPKpx0FW_B50.jpg?size=73x16&quality=96&type=album)

Отменил последнее действие.
![Отменил последнее действие.](https://sun9-46.userapi.com/s/v1/if2/KOVabl8oyf0wjvhj7J0lsD9QFQzlzyPTKOLwThUzyabDEm0iy3qO6wO3KU5rIfc7vLMoOFNVDvc33bPGJHzdOI3v.jpg?size=114x101&quality=96&type=album)

# Выводы

Познакомился с операционной системой Linux. Получил практические навыки работы с редактором vi.