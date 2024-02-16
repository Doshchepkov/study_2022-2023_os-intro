---
## Front matter
title: "Лабораторноая работа 1"
author: "Ощепков Дмитрий Владимирович"
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

Целью данной работы является приобретение практических навыков
установки операционной системы на виртуальную машину, настройки ми-
нимально необходимых для дальнейшей работы сервисов.

# Добавление образа
Скачал образ Rocky с сайта и добавил его в настройках
![Подключение образа](/home/dvothepkov/Лабы/Лаба1/images/1.jpg){#fig:001 width=70%}

# Настройка установщика 

![Настроил остальные пункты установщика](/home/dvothepkov/Лабы/Лаба1/images/3.jpg){#fig:003 width=70%}

# Завершил установку
![Загрузка](/home/dvothepkov/Лабы/Лаба1/images/5.jpg){#fig:005 width=70%}

# Конечные настройки

Добавил образ гостевой ОС и создал пользователя 

![Обратите внимание на имя пользваотеля](/home/dvothepkov/Лабы/Лаба1/images/6.jpg){#fig:006 width=70%}

# Выводы

Приобрел практические навыки
установки операционной системы на виртуальную машину, настройки ми-
нимально необходимых для дальнейшей работы сервисов.

# Доп вопросы
Команды: help, cd, ls, rm, chmod, kill

