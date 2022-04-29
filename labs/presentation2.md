---
## Front matter
lang: ru-RU
title:  Лабораторная работа 2
author: Аслиддин Ахлиддинзода
	Leonid A. Sevastianov\inst{1,3}
	\and
	Anton L. Sevastianov\inst{1}
	\and
	Edik A. Ayrjan\inst{2}
	\and
	Anna V. Korolkova\inst{1}
	\and
	Dmitry S. Kulyabov\inst{1,2}
	\and
	Imrikh Pokorny\inst{4}
institute: НФИ бд 01-21
	\inst{1}RUDN University, Moscow, Russian Federation
	\and
	\inst{2}LIT JINR, Dubna, Russian Federation
	\and
	\inst{3}BLTP JINR, Dubna, Russian Federation
	\and
	\inst{4}Technical University of Košice, Košice, Slovakia
date: NEC--2022.04.29.

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Лабораторная работа 2

## Цель работы

- Изучить идеологию и применение средств контроля версий.
- Освоить уменя по работе с git.

## Ход работы

- Завести учетную запичь на github.com
- Скачать и установить git

### Настройка конфигурации git
- Задаем имя и email владельца
- Настроим utf-8 в выводе сообщений git
- Настройте верификацию и подписание коммитов git
- Зададим имя начальной ветки
- Параметры autocrlf и safecrlf

### Создание ключей PGP и SSH 
- Создать ключ по алгоримту rsa и размером 4096 бит 
- Создать ключ по алгоритму еd25519 и размером 4096 бит 
- Генерируем PGP ключ
- Добавим RSA и PGP ключ в Github

### Создание шаблонов

- Создать папку для нашего репозитория 
- Создать репозиторий с помощью gh
- Склонировать репозиторий

### Настройка каталогов 

- Перейти в каталог 
- Удалить ненужные файлы
- Добавить файлы
- Сделать коммит изменений
- Отправить информацию на сервер

# Вывод
Изучил идеологию и применил средства контроля версий. Освоил по работе с git