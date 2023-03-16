---
## Front matter
title: "Презентация по проекту 2"
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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Зполнить сайт на основе гита (начало)

# Выполнение 

![Поменял главную фотографию](/home/dvothepkov/Screens/1.png){#fig:001 width=70%}

![Заполнил шапку сайта](/home/dvothepkov/Screens/2.png){#fig:002 width=70%}

![Сгенерировал пост на сайте](/home/dvothepkov/Screens/3.png){#fig:003 width=70%}

![Создал пост о гите](/home/dvothepkov/Screens/5.png){#fig:004 width=70%}

Между всем этим авторизовал свой гитхаб в терминале.

![Отправляю все на гит](/home/dvothepkov/Screens/6.png){#fig:005 width=70%}

Здесь можно лицезреть сам сайт: https://doshchepkov.github.io/
# Выводы

Заполнил сайт информацией о себе (начало)

# Список литературы{.unnumbered}

::: {#refs}
:::
