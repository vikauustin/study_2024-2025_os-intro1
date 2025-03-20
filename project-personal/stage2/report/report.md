---
## Front matter
title: "Индивидуальный проект"
subtitle: "Второй этап"
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

Добавить к сайту данные о себе

# Задание

Добавить данные о себе.
Написать два поста, один по прошедшей неделе, второй по выбору.

# Выполнение лабораторной работы

Разместить фотографию владельца сайта. (рис. [-@fig:001]).

![Переходим в папку admin и заменяем фотографию на собственную](image/1.jpg){#fig:001 width=70%}

Заполняем основные данные о себе(рис. [-@fig:002]).

![Конкретно имя и фамилию](image/2.jpg){#fig:002 width=70%}

Добавить информацию об интересах (Interests).Добавить информацию от образовании (Education)(рис. [-@fig:003]).

![Заполняем нашей информацией](image/3.jpg){#fig:003 width=70%}

Редактируем основной текст про About me на основном экране(рис. [-@fig:004]).

![Пишем про себя](image/4.jpg){#fig:004 width=70%}

Находим папку git - started(рис. [-@fig:005]).

![Добавляем фотографию поста](image/5.jpg){#fig:005 width=70%}

Заполняем пост по прошедшей неделе(рис. [-@fig:006]).

![Также заполняем наши данные](image/6.jpg){#fig:006 width=70%}

Пишем пост(рис. [-@fig:007]).

![Придумываем название заголовков](image/7.jpg){#fig:007 width=70%}

Второй пост по выбору стал про git(рис. [-@fig:008]).

![Заполняем summary, title](image/8.jpg){#fig:008 width=70%}

Нужно заполнить пост основной информацией(рис. [-@fig:009]).

![Рассказываем о версиях git](image/9.jpg){#fig:009 width=70%}

Запускаем сайт(рис. [-@fig:010]).

![Используем команду hugo server](image/10.jpg){#fig:010 width=70%}

Проверяем как создался сайт(рис. [-@fig:011]).

![Картинка и текст на месте](image/11.jpg){#fig:011 width=70%}

Подкаталоги welcome кликабельны(рис. [-@fig:012]).

![Переходим и смотрим](image/12.jpg){#fig:012 width=70%}

Пост про версии git.(рис. [-@fig:013]).

![Дата название и картинка отображаются](image/13.jpg){#fig:013 width=70%}


# Выводы

Выполнение второго этапа индивидуального проекта о создании  персонального сайта научного работника прошло успешно, а также получилось дoбавить к сайту данные о себе.
