---
## Front matter
title: "Презентация работа 6"
subtitle: "Дисциплина: Операционные системы"
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

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.

# Выполнение лабораторной работы

![Перезаписываю имена файлов из etc в свой файл и добавляю туда еще имена файлов из домашенго каталога](/home/dvothepkov/Screens/1.png){#fig:001 width=70%}

![Нахожу все файлы с разрешением .conf](/home/dvothepkov/Screens/2.png){#fig:002 width=70%}

![Нахожу в каталоге etc все файлы, имена которых начинаются с "h"](/home/dvothepkov/Screens/5.png){#fig:003 width=70%}

![Открываю gedit в фоновом режиме и узнаю информацию о процессе](/home/dvothepkov/Screens/7.png){#fig:004 width=70%}

![Останавливаю процесс](/home/dvothepkov/Screens/8.png){#fig:005 width=70%}

![Узнаю информацию о памяти с помощью указанных команд](/home/dvothepkov/Screens/9.png){#fig:006 width=70%}

# Выводы

Ознакомился с инструментами поиска файлов и фильтрации текстовых данных.
Приобрел практические навыки: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.

::: {#refs}
:::
