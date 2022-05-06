---
## Front matter
title: "Лабораторная работа 6"
subtitle: " Поиск файлов. Перенаправление ввода-вывода. Просмотр запущенных процессов"
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

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.

# Ход работы

Записал в файл file.txt названия файлов,содержащихся в каталоге /etc.
![Записал в файл file.txt названия файлов,содержащихся в каталоге /etc.](https://sun9-44.userapi.com/s/v1/if2/zBZYY5wCbv6tHZBoYlnusOFNXGze3SEtZ41sI7VZnI2sRr_DyhI2b2mvLwl8qhvDOEktsibiLbHPbi7Q3DqmZ4hx.jpg?size=261x240&quality=96&type=album)

Вывел имена всех файлов из file.txt,имеющих расширение .conf,после чего записал их в новый текстовой файл conf.txt
![Вывел имена всех файлов из file.txt,имеющих расширение .conf,после чего записал их в новыйтекстовой файл conf.txt](https://sun9-66.userapi.com/s/v1/if2/zvBzz2KA6HTOoGv5jSYyLfOVFn7fiYi5wWgkA97-1OBWi4BQ-UUhRvEUQFnzWXCk8t3WIh7Fe2eloMLW299QPEO6.jpg?size=391x24&quality=96&type=album)

Записал в новый текстовый файл
![Записал в новый текстовый файл](https://sun9-43.userapi.com/s/v1/if2/z6VGEmrIPQHUd6CddmS74_DBG5cCuNYZSd6zZs_1_bOZfsdieuoe3gINPm8uG_nv8rApmDUbmfSb1lP7OzMYF1RM.jpg?size=114x264&quality=96&type=album)

Определил,какие файлы в вашем домашнем каталоге имеют имена,начинавшиеся с символа c.
![Определил,какие файлы в вашем домашнем каталоге имеют имена,начинавшиеся с символа c.](https://sun9-31.userapi.com/s/v1/if2/kAHvKf8tdRbWCV4TJAns5Stpj3hc0cTULctm19jBwEZjKl4bCJ3rRqRyZNPs793Ibk7Otxz4tVPVNUJ4fwOMHr9g.jpg?size=421x121&quality=96&type=album)

Вывел на экран (по странично) имена файлов из каталога /etc,начинающиеся с символа h.
![Вывел на экран (по странично) имена файлов из каталога /etc,начинающиеся с символа h.](https://sun9-23.userapi.com/s/v1/if2/UXurpoWSClAgXrk90wPkvrXvBoqwwaaDmjuBEzUF0ZNTjETNcXhuwD-ROrL_sWb7CnxoWQdVUUAECyrBrPoHMa5g.jpg?size=320x105&quality=96&type=album)

Запустил в фоновом режиме процесс,который будетзаписывать в файл ~/logfile файлы,имена которых начинаются с log.
![Запустил в фоновом режиме процесс,который будетзаписывать в файл ~/logfile файлы,имена которых начинаются с log.](https://sun9-77.userapi.com/s/v1/if2/aiWnGrMeKFojulrQ1udztNC0N0cATMTH76687kv_YvrryurW46ysSoWo1FAgbhjsvuRKmztISQalkiDW1HZBk-XF.jpg?size=418x73&quality=96&type=album)

Удалил этот файл.
![Удалил этот файл.](https://sun9-2.userapi.com/s/v1/if2/SzZSh902QQr-zQcJqrj8KtZaB1fxkumobRPXwYfW_iRPT7uFdnryA6CjuaPWSxAAuyYttoeYcs9XgJ8sMEIKXOQV.jpg?size=416x83&quality=96&type=album)

Запустил из консоли в фоновом режиме редактор gedit. Завершил процесс gedit с помощью kill.
![Запустил из консоли в фоновом режиме редактор gedit. Завершил процесс gedit с помощью kill.](https://sun9-5.userapi.com/s/v1/if2/SUzKJedj4hAj6Bj9h07B8LhwGjfs957ALooI84WxdL1UN1fXzYx4RvNu8ygL-Hc4POKwR-ApDqOxESTlBG30Fpxv.jpg?size=432x143&quality=96&type=album)

Выполнил команды df и du.
![Выполнил команды df и du.](https://sun9-30.userapi.com/s/v1/if2/iaJGy8p6fhr1bypha_UbFt7INsKtplHsbHdctbi6Zwf151-NrjQyxuK0d67BRS6CBI8W7loxETnhjtVR-3pq47TJ.jpg?size=216x24&quality=96&type=album)

Вывел имена всех директорий,имеющихся в вашем домашнем каталоге.
![Вывел имена всех директорий,имеющихся в вашем домашнем каталоге.](https://sun9-76.userapi.com/s/v1/if2/mw4YcXIkVyGYivd6tn8IcuCySbFMSkrkJly568A2LLqRoOtglFfXDFCdFZhLKhIf578MpLw571BwsS_JdhG_rGeG.jpg?size=285x15&quality=96&type=album)

# Выводы

Ознакомился с инструментоми поиска файлов и фильтрации текстовых данныхо. Приобрел практическиме навыкм по управлению процессами по проверке использования диска и обслуживанию файловых систем.
