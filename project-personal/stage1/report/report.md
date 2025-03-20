---
## Front matter
title: "Индивидуальный проект"
subtitle: "Первый этап"
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

Выполнение первого этапа индивидуального проекта о создании  персонального сайта научного работника, создать и выгрузить на github шаблон сайта

# Задание

Установить необходимое программное обеспечение.
Скачать шаблон темы сайта.
Разместить его на хостинге git.
Установить параметр для URLs сайта.
Разместить заготовку сайта на Github pages.

# Выполнение лабораторной работы

Загружаем файл hugo из гитхаба (рис. [-@fig:001]).

![Проверяем наличие файла командой ls и распаковываем его](image/1.jpg){#fig:001 width=70%}

Переносим файл в /usr/local/bin(рис. [-@fig:002]).

![Проверяем перенос командой ls](image/2.jpg){#fig:002 width=70%}

Создаем репозиторий на гитхабе(рис. [-@fig:003]).

![Называем его project](image/3.jpg){#fig:003 width=70%}

Переходим в рабочий каталог и клонируем туда репозиторий новый(рис. [-@fig:004]).

![Клонируем командой git clone --recursive](image/4.jpg){#fig:004 width=70%}

Переходим в папку проекта и смотрим содержимое(рис. [-@fig:005]).

![Команда ls](image/5.jpg){#fig:005 width=70%}

Необходимо установить go(рис. [-@fig:006]).

![Вводим команду](image/6.jpg){#fig:006 width=70%}

Используем одну и основных команд для создания сайтов(рис. [-@fig:007]).

![Вводим команду и удаляем файл, так как без этого сайт не откроется](image/7.jpg){#fig:007 width=70%}

Запускаем команду hugo server, чтобы получить ссылку(рис. [-@fig:008]).

![Запускаем](image/8.jpg){#fig:008 width=70%}

командо выполнилась успешно и мы копируем ссылку и запускаем ее(рис. [-@fig:009]).

![В левом окне виден сайт](image/9.jpg){#fig:009 width=70%}

Создаем новый репозиторий для сайта(рис. [-@fig:010]).

![Называем его vikauustin.github.io](image/10.jpg){#fig:010 width=70%}

Переходим в рабочую папку и клонируем его туда, создаем ветвь и добавляем в репозиторий файл(рис. [-@fig:011]).

![Называем файл README.md](image/11.jpg){#fig:011 width=70%}

Отправляем первый файл в пустой репозиторий(рис. [-@fig:012]).

![Используем классические команды для отправки](image/12.jpg){#fig:012 width=70%}

Переходим в первый репозиторий и используем команду git submodule чтобы сохранить один репозиторий в качестве подкаталога другого(рис. [-@fig:013]).

![Заодно удаляем файл public снова](image/13.jpg){#fig:013 width=70%}

Отправляем все файлы на гитхаб(рис. [-@fig:014]).

![Коммитим](image/14.jpg){#fig:014 width=70%}

Используем команду git push для отпарвки(рис. [-@fig:015]).

![Все выполнено успешно, сайт запускается по ссылке https://vikauustin.github.io](image/15.jpg){#fig:015 width=70%}


# Выводы

Выполнение первого этапа индивидуального проекта о создании  персонального сайта научного работника прошло успешно, а также получилось создать и выгрузить на github шаблон сайта, под своей ссылкой.


