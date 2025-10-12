---
## Front matter
title: "Лабораторная работа №3"
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

1. Изучение процедур и функций в Python
2. Знакомство с модулем math

# Выполнение лабораторной работы

Выполнения задачи №1. (рис. [-@fig:001]).

![Задание №1](image/1.png){#fig:001 width=70%}

Выполнения задачи №2. (рис. [-@fig:002]).

![Задание №2](image/2.png){#fig:002 width=70%}

Выполнения задачи №2. (рис. [-@fig:003]).

![Задание №3](image/3.png){#fig:003 width=70%}

Выполнения задачи №4. (рис. [-@fig:004]).

![Задание №4](image/4.png){#fig:004 width=70%}

Выполнения задачи №5.1. (рис. [-@fig:005]).

![Задание №5.1](image/5.1.png){#fig:005 width=70%}

Выполнения задачи №5.2. (рис. [-@fig:006]).

![Задание №5.2](image/5.2.png){#fig:006 width=70%}

Выполнения задачи №5.3.(рис. [-@fig:007]).

![Задание №5.3](image/5.3.png){#fig:007 width=70%}

Выполнения задачи №6.1. (рис. [-@fig:008]).

![Задание №6.1](image/6.1.png){#fig:008 width=70%}

Выполнения задачи №6.2. (рис. [-@fig:009]).

![Задание №6.2](image/6.2.png){#fig:009 width=70%}

Выполнения задачи №6.3. (рис. [-@fig:010]).

![Задание №6.3](image/6.3.png){#fig:010 width=70%}

# Ответы на контрольные вопросы

1. В чем смысл написания функций?
   Смысл написания функций в программировании — упростить код, сделать его многократно используемым, структурированным и легко читаемым.
2. В какой момент Python создает функцию?
   Python создает функцию в момент, когда интерпретатор встречает её объявление (определение) с помощью ключевого слова def.
3. Что функция возвращает, если в ней нет ни одного оператора return?
   Если в функции нет оператора return, она вернёт специальное значение, в Python — None.
4. Когда выполняется код, вложенный внутрь оператора определения функции?
   Код внутри оператора определения функции не выполняется в момент её определения, а только тогда, когда эта функция вызывается


# Выводы

При выполнении данной лабораторной работы я ознакомилась с библиотекой math и научилась создавать и вызывать функции в питоне.
