---
## Front matter
title: "Лабораторная работа 5"
subtitle: "Анализ файловой системы Linux. Команды для работы с файлами и каталогами"
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

Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами,по управлению процессами (и работами),по проверке исполь-
зования диска и обслуживанию файловой системы.

# Ход работы



![Выполнил все примеры](https://sun9-17.userapi.com/s/v1/if2/EHEKGeud3hB5_y2AZ8MDox9fu53NhwaNUGLYs7byTECYd58cNEoHFWD9wSvlh9-NNixhGmmqqnshiBioV-1B16d3.jpg?size=671x495&quality=96&type=album)

![Переместил файл equipment в каталог ~/ski.plases. Переименовал файл ~/ski.plases/equipment в ~/ski.plases/equiplist. Создал файл abc1 и скопировал туда ~/ski.plases,назвал его equiplist2](https://sun9-10.userapi.com/s/v1/if2/Wt9QWBb7B-kYQdRFqjXe1op1wEbR80L-KHzynfuFwJX_cWlOMbDTZEFW4Lzas5GgTRWA-iJei_-6TVhZViJxsABN.jpg?size=743x401&quality=96&type=album)

![Создал и переместил каталог ~/newdir в каталог ~/ski.plases и назовите его plans.](https://sun9-21.userapi.com/s/v1/if2/NylsCDU3z-g3eYkhWrCMwiDCs2s4uNhUpCjiYBaiNyIkKruRqIjv3PvIEkrAzJgaBGLzNg51aNabbKv9AKNnbxPI.jpg?size=494x219&quality=96&type=album)

![Создал нужные файлы](https://sun9-17.userapi.com/s/v1/if2/-zgfS4JZvMUeeKdIcAtzLS6nC21r8y6inGywcdr1nvIOvA7yXc0PdZvobJv38B0sqPZ1UdCmvU2OBq4qyWKQmAnA.jpg?size=566x20&quality=96&type=album)

![Изменил права доступа с помощью команды chmod](https://sun9-86.userapi.com/s/v1/if2/N84DacYxU3UmCWx137zCFzGGweSbYf9qCAol6I5Rb7e44ljAe8gT8nRgYkq0uL0SLPa8VRU1ERvu6rm5zx6dRbDs.jpg?size=545x256&quality=96&type=album)

![Просмотрел содержимое файла /etc/password](https://sun9-43.userapi.com/s/v1/if2/5PZl_JDvoCk_34A1vZg_gy9UqgGdZCCNs6vcI4_X-ScJ7HaK7HWf_4k3ti7r1IsdCePtoWdwSrZUU_SPmt7r4A_x.jpg?size=711x540&quality=96&type=album)

![Скопировал файл /feathers в файл /file.old. Переместил файл /file.old в каталог ~/play. Скопировал каталог /play в каталог /fun. Переместил каталог /fun в каталог /play и назвал его games.](https://sun9-38.userapi.com/s/v1/if2/Tb6TX4xEMQb2rY_GdH-8cs1QQ1dXgdizHw-XUuDxRj53eohiTurcSEKokpV8AqUfNKXk0vVZt9uk7gbrHl0cjNFt.jpg?size=608x363&quality=96&type=album)

![Лишил владельца файла /feathers права на чтение.](https://sun9-38.userapi.com/s/v1/if2/dyOeRb-eMOIEG5JFs_i_yzl4hYo0sv5odjobeoXGQ1J8K2y4-AHE0-U1ELmV_9jL2w_MJzPVbSiMg3grBEmX8RAI.jpg?size=567x129&quality=96&type=album)
![Вернул владельцу право на чтение. Лишил владельца каталога play права на выполнение. Прочитал краткое описание команд mount,fsck,mkfs,kill с помощью man](https://sun9-29.userapi.com/s/v1/if2/NxbbgrHqkwuYAlgrsxniU73TO8gs66LUcmr0gLRf4Ah0Xfq8pwDWU-LqnRlXxxwf2an2YGi1JqocrBda7rbN1SDa.jpg?size=679x560&quality=96&type=album)

# Выводы

Ознакомился с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобрел практических навыков по применению команд для работы с файлами и каталогами,по управлению процессами (и работами),по проверке исполь-
зования диска и обслуживанию файловой системы.
