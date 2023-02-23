---
## Front matter
title: "Отчет по проекту 1"
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

Создать сайт на основе гита (начало)

![Скачал все, что нужно](/home/dvothepkov/крины/2.jpeg){#fig:001 width=70%}

Распаковал по папкам, как было в руководстве, доустановил голанг, создал папки блог и бин.

![Прописал команду из руководства](/home/dvothepkov/крины/3.jpeg){#fig:002 width=70%}

![Открыл сайт, который поддерживается только на моем устройстве](/home/dvothepkov/крины/4.jpeg){#fig:003 width=70%}

![Создал пустой репозиторий](/home/dvothepkov/крины/5.jpeg){#fig:004 width=70%}

![Отклонировал пустой репозиторий](/home/dvothepkov/крины/6.jpeg){#fig:005 width=70%}

Между всем этим авторизовал свой гитхаб в терминале.

![Прописываю команду submodule и потом создаю ранее удаленный файл public](/home/dvothepkov/крины/7.jpeg){#fig:006 width=70%}

![Работаю с гитом: добавляю коммиты и прочее](/home/dvothepkov/крины/8.jpeg){#fig:007 width=70%}

![После пуша на гит все файлы перенеслись на гит, после чего мой сайт получил возможность открываться через гит.](/home/dvothepkov/крины/9.jpeg){#fig:008 width=70%}


# Выводы

Создал сайт на основе гита (начало)

# Список литературы{.unnumbered}

::: {#refs}
:::
