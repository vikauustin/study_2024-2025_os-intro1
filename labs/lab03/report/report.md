---
## Front matter
title: "Лаборатораня работа №3"
subtitle: "Отчет"
author: "Устинова Виктория Вадимовна"

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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown

# Задание

Оформить лабораторную работу №2 в формате Markdown


# Выполнение лабораторной работы

Оформляем основные данные(рис. [-@fig:001]).

![Лабораторная номер 2 и ФИО](image/1.jpg){#fig:001 width=70%}

Цель работы(рис. [-@fig:002]).

![Пишем цель работы номер 2](image/2.jpg){#fig:002 width=70%}

Копируем здания из лабораторной(рис. [-@fig:003]).

![Вставляем задания](image/3.jpg){#fig:003 width=70%}

Выполняем основную часть(рис. [-@fig:004]).

![Пишем все задания и указываем ссылку на рисунки](image/4.jpg){#fig:004 width=70%}

Выводы(рис. [-@fig:005]).

![Пишем вывод](image/5.jpg){#fig:005 width=70%}

Ответы на вопросы(рис. [-@fig:006]).

![Вставляем ответы на вопросы из 2 лабораторной](image/6.jpg){#fig:006 width=70%}

Переходим в каталог и пишем команду make(рис. [-@fig:007]).

![Вводим команду и ждем пока файл запустится](image/7.jpg){#fig:007 width=70%}

Переходим на файл(рис. [-@fig:008]).

![Он успешно создан](image/8.jpg){#fig:008 width=70%}

# Выводы

Мы научились оформлять отчёты с помощью легковесного языка разметки Markdown и успешно сделали в нем лабораторную работу №2


