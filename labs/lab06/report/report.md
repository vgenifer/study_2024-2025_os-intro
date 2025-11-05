---
## Front matter
title: "Лабораторная работа №5"
subtitle: "Введение в программирование на языке Python"
author: "Виеру Женифер"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Работать с файлами а питоне.

# Выполнение лабораторной работы

Напишите программу , которая читает текстовый файл и выводит его содержимое на экран (рис. [-@fig:001]).

![Задание №1](image/1.png){#fig:001 width=70%}

Создайте программу , которая копирует содержимое одного текстового файла в другой (рис. [-@fig:002]).

![Задание №2](image/2.png){#fig:002 width=70%}

Напишите функцию, которая принимает имя файла и возвращает количество строк в этом файле. (рис. [-@fig:003]).

![Задание №3](image/3.png){#fig:003 width=70%}

Реализуйте программу , которая читает файл с числами и записывает только четные числа в новый файл. (рис. [-@fig:004]).

![Задание №4](image/4.png){#fig:004 width=70%}

Напишите программу , которая объединяет содержимое нескольких текстовых файлов в один. (рис. [-@fig:005]).

![Задание №5](image/5.png){#fig:005 width=70%}

Создайте программу , которая считывает данные из JSON-файла и выводит их в удобочитаемом формате(рис. [-@fig:006]).

![Задание №6](image/6.png){#fig:006 width=70%}



