---
## Front matter
title: "Лабораторная работа №4"
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

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки

# Выполнение лабораторной работы 

Определил полное имя моего домашнего каталога. Далее относительно этого каталога буду выполняться последующие упражнения

![Перешел в каталог /tmp, вывеле на экран содержимое каталога /tmp. Для этого использовал команду ls с различными опциями](/home/dvothepkov/СКРИНЫ/1.png){#fig:001 width=70%}

![Определил, есть ли в каталоге /var/spool подкаталог с именем cron](/home/dvothepkov/СКРИНЫ/2.png){#fig:002 width=70%}

![Перешел в мой домашний каталог и вывел на экран его содержимое. Определил, кто является владельцем файлов и подкаталогов](/home/dvothepkov/СКРИНЫ/3.png){#fig:003 width=70%}

![Посоздавал различные каталоги](/home/dvothepkov/СКРИНЫ/4.png){#fig:004 width=70%}

# Выводы

Приобрел практические навыки взаимодействия пользователя с системой посредством командной строки.

:::
