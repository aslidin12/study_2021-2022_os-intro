---
## Front matter
title: "Лабораторная работа 9"
subtitle: " ТТекстовой редактор emacs"
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

Познакомиться с операционной системой Linux.Получить практические навыки рабо-
ты с редактором Emacs.

# Ход работы

Создал файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f и пешел в него.
![Создал файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f и пешел в него.](hhttps://sun9-23.userapi.com/s/v1/if2/Xd04VtiPvfROnbzqZylZChIbA_v-fkCl54VJUgk2Crubwr4KBm-Cqx_ygGPNFrYVySCn1heQrPHBhneb5WmuWAtW.jpg?size=646x191&quality=96&type=album)

Ввел текст.
![Ввел текст.](https://sun9-82.userapi.com/s/v1/if2/L3P_MAdIg3mmjwIk0b4P3AGsNOUjdI6SQ_9wBg8chhgxPFccDJ1TeLmvX4rhmNzFkM6XRC1RZr7kqQQxK4K4Bzk0.jpg?size=185x257&quality=96&type=album)

Вырезал одной командой целую строку (С-k) и Вставил эту строку в конец файла (C-y).
![Вырезал одной командой целую строку (С-k) и Вставил эту строку в конец файла (C-y).](https://sun9-34.userapi.com/s/v1/if2/XplfhkR2XJqLzdpUDOh6vFCMX63aqHh_yIM2721upA-MOPGkmp86Uag9wLYik-5ETtW4qmXTdy8rGmc8wz8fSrzq.jpg?size=125x168&quality=96&type=album)

Переместился во вновь открытое окно (C-x) o со списком открытых буферов и переключился на другой буфер.
![Переместился во вновь открытое окно (C-x) o со списком открытых буферов и переключился на другой буфер.](https://sun9-3.userapi.com/s/v1/if2/lRE-dXokF7kVaB-ipPAI40d3QUS7Nyx3i47HehffEa1KRJZFY1TGBsuYIhvxD-f3IgHqq-4dOIWQM7dC-74yASdD.jpg?size=441x422&quality=96&type=album)

Закрыл это окно (C-x 0). 
![Закрыл это окно (C-x 0).](https://sun9-17.userapi.com/s/v1/if2/eOIpAc-AAaYLzjzZNsS0BWxKsoxNBYWL2sBZi8KIdajtmofBoqFx9z0r_FKPh3STXuwg66LWsGtTsbjZ9in94SP8.jpg?size=427x432&quality=96&type=album)

Поделил фрейм на 4 части.
![Поделил фрейм на 4 части.](https://sun9-22.userapi.com/s/v1/if2/-U2nfmRrW8l8_bnpkqFLBNEcZW6HsuPizNJ1SkHX4nWpN05MJ8Cv16NrwYWlU3ExTgXehaKYi_-QTLkXSFhKSLfQ.jpg?size=455x480&quality=96&type=album)

В каждом открыл новый буфер и ввел несколько строк.
![В каждом открыл новый буфер и ввел несколько строк.](https://sun9-52.userapi.com/s/v1/if2/ruCQSRNnbbEQgHkH2j9EzVJhXfTu776u94fznTpxHR4qM4RFQPgvp-9Z5xyUyYOvr3MBKTOTGAIGw_gm8rutBEA1.jpg?size=568x475&quality=96&type=album)

Переключился в режим поиска (C-s) и найдите несколько слов, присутствующих в тексте.
![Переключился в режим поиска (C-s) и найдите несколько слов, присутствующих в тексте.](https://sun9-44.userapi.com/s/v1/if2/cJvi07Rxp7mGxvettTh2I0HC_sYmZJ9thqmiNqXZEsDY-BrUHsmdXOBzptTmONEO-j_2BkXo3rh6PGBbTM6_NX-t.jpg?size=558x477&quality=96&type=album)

# Выводы

Познакомился с операционной системой Linux.Получил практические навыки рабо-
ты с редактором Emacs.