---
## Front matter
title: "Лабораторная работа 13"
subtitle: " Средства, применяемые при разработке программного обеспечения в ОС типа UNIX/Linux. "
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

Приобрести простейшие навыки разработки,анализа,тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

# Ход работы

В домашнем каталоге создал подкаталог ~/work/os/lab_prog.
![В домашнем каталоге создал подкаталог ~/work/os/lab_prog.](https://sun9-85.userapi.com/s/v1/if2/suG0Kdu0FpjKsdNVKL9PYs9LOYuuyK6JklSKVNB53ZyXyWNfVH9w_QQNVA-5aHW9R7sPZSbVKfkbIvqv2OfivZBe.jpg?size=257x38&quality=96&type=album)

Создал в нём файлы: calculate.h,calculate.c,main.c. Заполнил все три файла кодами.
![Создал в нём файлы: calculate.h,calculate.c,main.c. Заполнил все три файла кодами.](https://sun9-54.userapi.com/s/v1/if2/Iil6wzKl8YHgjtHZaVOm8Fp-xMA-0V_7spMx67EkMioCehNGhLafPsV2Gv5pHv0dD9inQQJ7-kNDF1CM4Vlc0Xi1.jpg?size=308x75&quality=96&type=album)

calculate.h
![calculate.h](https://sun9-60.userapi.com/s/v1/if2/piNmGjmIlALPfZqYf1TPCBs4Tfxp7YI_mdwtHAkE1y-5BgOToW9sxaUX9030zY0J_acFf9kU4Yxa1FShIhNDfulG.jpg?size=241x197&quality=96&type=album)

calculate.c
![calculate.c](https://sun9-2.userapi.com/s/v1/if2/z7f3yKOu9ic-8PaC_J3DoZckL5ntVsq6f2uAH0L8idQe24D59gz49_MJv0VxIqVDtnrUF2W87nNy1mPDDIXhXHi4.jpg?size=276x73&quality=96&type=album)

main.c.
![main.c](https://sun9-1.userapi.com/s/v1/if2/mRWPBWBQ8-gWOgLesXhRHo6tW6D-uTBuccuLOgFRyezpkgL1Pcd8qWep6QD8dEVf-BQeGZfOgu-YYqdzfx_QuIhZ.jpg?size=310x182&quality=96&type=album)

Выполнил компиляцию программы посредством gcc:
![Выполнил компиляцию программы посредством gcc:](https://sun9-6.userapi.com/s/v1/if2/5Thsiwwsfao8HAzBEXP5SimiYaNqplseH8nJHZ4t8u0jMAV7HsayNpAaXSFgldsWnoL-Y8BlTyXaKBBbzxsK3yKr.jpg?size=411x39&quality=96&type=album)

Создал Makefile со следующим содержанием:
![Создал Makefile со следующим содержанием:](https://sun9-85.userapi.com/s/v1/if2/nn4ok-Xz2fE7JPBEbJQHqeXF0UOy1yz9IxGs_1jpbmvwsdsMJ2695PFe-eXmitdi3z0D4BV69O2gSFetCOg6l7pu.jpg?size=305x30&quality=96&type=album)

Makefile
![Makefile](https://sun9-30.userapi.com/s/v1/if2/_OKCoK28RlNxOjXhTJBUmBZOClfzjkA2DKmskKixQ8iD1w3gyIdfcD8r1XtvVdgtl-_IwkXqq67r6u0fgQq2x67d.jpg?size=256x125&quality=96&type=album)

С помощью gdb выполнил отладку программы calcul.
![С помощью gdb выполнил отладку программы calcul.](https://sun9-55.userapi.com/s/v1/if2/nSH3Q3E8hZqInr6Z852Kgu-MThmxNU4O6jWJqHI4kc4rAKcuy7ssMBADUk9982rb9lM4jqq1hn61d1KMzCHXXsGA.jpg?size=395x165&quality=96&type=album)


# Выводы

Приобрел простейшие навыки разработки,анализа,тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.