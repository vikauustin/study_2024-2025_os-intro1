---
## Front matter
title: "Индивидуальный проект этап 4"
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

Написать новый пост по прошедшей неделе и пост по выбору, а также добавить и изменить ссылки на собственные сайты.

# Задание

Добавить к сайту ссылки на научные и библиометрические ресурсы.Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте.Сделать пост по прошедшей неделе.Добавить пост на тему по выбору: Оформление отчёта. Создание презентаций.Работа с библиографией

# Выполнение лабораторной работы

Добавить информацию о ссылках(рис. [-@fig:001]).

![Регестрируемся на всех сайтах и добавляем ссылки](image/1.jpg){#fig:001 width=70%}

Нписали пост по прошедшей неделе(рис. [-@fig:002]).

![Пост кликабельный](image/2.jpg){#fig:002 width=70%}

Написали интересный пост про презетации(рис. [-@fig:003]).

![Вставили красивую картинку](image/3.jpg){#fig:003 width=70%}

Вид на сайте(рис. [-@fig:004]).

![Вот как выглядят посты на сайте](image/4.jpg){#fig:004 width=70%}

# Выводы

Мы успешно выполнили данные нам задания, составили красивые посты и дополнили ссылки.

