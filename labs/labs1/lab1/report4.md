---
## Front matter
title: "Лабораторная работа 4"
subtitle: "Основы интерфейса взаимодействия
пользователя с системой Unix на уровне командной строки"
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

Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.

# Ход работы



![Узнаем полное имя домашнего каталога](https://sun9-69.userapi.com/s/v1/if2/QGEt98u6KACiJt3WBkHVAXpZMk4bmADupmrbTVDnt9JUGC31Q11bt6yFmTwJVT6hg6r3sU8x_Yp9skrSwidJ889l.jpg?size=183x26&quality=96&type=album)

![Выведем на экран содержимое каталога /tmp.](https://sun9-3.userapi.com/s/v1/if2/BkxliEc87WlBHedPhXhdvAwyadUs_-2NL0YsnZgbEbrEfqEo91s24Bdpv9qeJU1BBkRAf7AzvMf7AxaCSIZH1HKz.jpg?size=445x283&quality=96&type=album)

![Определим,есть ли в каталоге /var/spool подкаталог с именем cron?](https://sun9-11.userapi.com/s/v1/if2/RysL_7zrYhMxaz5xQDhLXOjY0qFlsfd4qVY6oh2Wm3yhMaR6RQtjJ-JSoj1LYS5wf755n82zbe5abwXGFdTZNXrD.jpg?size=252x36&quality=96&type=album)

![В домашнем каталоге создадим новый каталог с именем newdir. В каталоге ~/newdir создадим новый каталог с именем morefun](https://sun9-34.userapi.com/s/v1/if2/c85X7KHnpTGbHKMVIysF3h3QE9GvIJXZsyjH1jVhy5qse7zoIswN0lHTpxygcQcjZr_L80w2MHMmzZB0jguLvCO9.jpg?size=417x108&quality=96&type=album)

![В домашнем каталоге создадим одной командой три новых каталога с именами letters,memos,misk.Затем удалим эти каталоги одной командой.](https://sun9-68.userapi.com/s/v1/if2/uBSsE4GNQNDThDWz4tQXfGZK8pcGotgudiW3VItee_OfI3eHtZFGtQ-vcLyAxeuIC3j27hGtf5eMuIFlx6JMEt4O.jpg?size=308x70&quality=96&type=album)

![Используем команду man для просмотра описания следующих команд: cd,pwd,mkdir,rmdir,rm.](https://sun9-77.userapi.com/s/v1/if2/Jz_ThH0vywrUcf1O5wD0gSPzASzVf8xNrZfmo2xrHIiwUS1FOzh0wAPGtOQuSF0Q5vpaC7WjxVrD6Z47cVZd2f5s.jpg?size=209x57&quality=96&type=album)

![Используем команду history для получения информации](https://sun9-88.userapi.com/s/v1/if2/xuoDQ8YHxWkxFBONVzImWuj4Pd-BpVgmZwQTNWkOTXBqKyuLqI-KLRauwU7AzQ1tB4JK1zFBO5VTFEi6PUG60Fl1.jpg?size=189x195&quality=96&type=album)

# Выводы

Приобрел практические навыки взаимодействия пользователя с системой по-
средством командной строки.
