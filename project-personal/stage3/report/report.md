---
## Front matter
title: "Отчет по выполнению третьего этапа индивидуального проекта"
subtitle: "Отчет"
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

При выполнение данного этапа моя цель добавить информацию о навыках (Skills), добавить информацию об опыте (Experience),добавить информацию о достижениях (Accomplishments) и сделат пост по прошедшей неделе и язык разметки Markdown.

# Задание

Добавить информацию о навыках (Skills).
Добавить информацию об опыте (Experience).
Добавить информацию о достижениях (Accomplishments).
Сделать пост по прошедшей неделе.
Добавить пост на Язык разметки Markdown.


# Выполнение лабораторной работы

Для начала я отрыла файл work/blog/content/admin и рассписала свои навыки, опыт и достижении.(рис. [-@fig:001]).

![Добавление информацию о навыках, об опыте и о достижениях.](image/1.png){#fig:001 width=70%}

Потом я начала писать пост про "Язык разметки Markdown." (рис. [-@fig:002]).

![Язык разметки Markdown.](image/2.png){#fig:002 width=70%}

Потом я начала писать пост про свою неделю. (рис. [-@fig:003]).

![Пост по прошедшей неделе.](image/3.png){#fig:003 width=70%}

# Выводы

При выполнении данного этапа я добавила больше нформации о себя(навыки, опыт и достижении) и сделала пост про языке разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
