---
## Front matter
title: "Презентация 10"
subtitle: "Дисциплина: Архитектура компьютеров"
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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать
небольшие командные файлы.

# Выполнение лабораторной работы

![Написал первый код](/home/dvothepkov/Screens/1.png){#fig:001 width=70%}

![Запустил код](/home/dvothepkov/Screens/2.png){#fig:002 width=70%}

![Написал второй код](/home/dvothepkov/Screens/3.png){#fig:003 width=70%}

![Взял готовую замену для ls из лекции](/home/dvothepkov/Screens/4.png){#fig:004 width=70%}

![Написал код для поиска файлов определенного формата](/home/dvothepkov/Screens/6.png){#fig:005 width=70%}

![Запустил код, осуществил поиск](/home/dvothepkov/Screens/5.png){#fig:006 width=70%}
# Выводы

Изучил основы программирования в оболочке ОС UNIX/Linux. Научился писать
небольшие командные файлы.

# Список литературы{.unnumbered}

::: {#refs}
:::
