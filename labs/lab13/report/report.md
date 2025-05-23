---
## Front matter
title: "Лабораторная работа №13"
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

Изучить основы программирования в оболочке ОС UNIX. Научится писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

# Задание

1. Используя команды getopts grep, написать командный файл, который анализирует
командную строку с ключами

2. Написать на языке Си программу, которая вводит число и определяет, является ли оно
больше нуля, меньше нуля или равно нулю. 

3. Написать командный файл, создающий указанное число файлов, пронумерованных
последовательно от 1 до 𝑁

4. Написать командный файл, который с помощью команды tar запаковывает в архив
все файлы в указанной директории.

# Выполнение лабораторной работы

Выполняем первое задание,ключи: -n — выдавать номера строк, iinputfile — прочитать данные из указанного файла(рис. [-@fig:001]).

![Написали командный файл](image/1.jpg){#fig:001 width=70%}

Текс файла(рис. [-@fig:002]).

![Файл txt](image/2.jpg){#fig:002 width=70%}

Используем определенные ключи(рис. [-@fig:003]).

![Правильный вывод](image/3.jpg){#fig:003 width=70%}

Написать программу, которая определяет число > < нуля(рис. [-@fig:004]).

![Пишем программу в 2.с](image/4.jpg){#fig:004 width=70%}

Открываем программу(рис. [-@fig:005]).

![Смотрим вывод](image/5.jpg){#fig:005 width=70%}

Команд-
ный файл должен вызывать эту программу и, проанализировав с помощью команды
$?, выдать сообщение о том, какое число было введено.(рис. [-@fig:006]).

![Используем расширение 2.sh](image/6.jpg){#fig:006 width=70%}

Открываем программу(рис. [-@fig:007]).

![Смотрим вывод](image/7.jpg){#fig:007 width=70%}

Число файлов,
которые необходимо создать, передаётся в аргументы командной строки. Этот же ко-
мандный файл должен уметь удалять все созданные им файлы (рис. [-@fig:008]).

![Пишем программу](image/8.jpg){#fig:008 width=70%}

Открываем ее(рис. [-@fig:009]).

![Показывает создание и удаление](image/9.jpg){#fig:009 width=70%}

Написать командный файл, который с помощью команды tar запаковывает в архив
все файлы в указанной директории(рис. [-@fig:010]).

![Расширение sh, пишем командный файл](image/10.jpg){#fig:010 width=70%}

Заходим в новую папку (рис. [-@fig:011]).

![Распаковываем](image/11.jpg){#fig:011 width=70%}

# Выводы

Мы успешно изучили основы программирования в оболочке ОС UNIX. Научились писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

## Ответы на контрольные вопросы

1.  getopts: Предназначена для разбора параметров командной строки в скриптах. Она обрабатывает аргументы, начинающиеся с дефиса (-), и позволяет удобно получать значения параметров.

2.  Метасимволы (в генерации имён файлов): Метасимволы (например, *, ?, []) используются для *подстановки имён файлов* (globbing).  Они позволяют выбрать группу файлов, соответствующих шаблону.

3.  Операторы управления действиями: Это в основном операторы, связанные с условиями:
    *   && (И): Выполнить вторую команду только если первая завершилась успешно (с кодом выхода 0).
    *   || (ИЛИ): Выполнить вторую команду только если первая завершилась неуспешно (с кодом выхода не 0).
    *   ! (НЕ): Инвертирует код возврата.

4.  Операторы прерывания цикла:
    *   break: Немедленно прерывает цикл и передает управление следующей команде после цикла.
    *   continue:  Переходит к следующей итерации цикла, пропуская оставшиеся команды в текущей итерации.

5.  false и true:
    *   false: Команда, которая всегда завершается с кодом выхода, отличным от нуля (обычно 1).  Используется для создания условий, которые всегда будут ложными.
    *   true: Команда, которая всегда завершается с кодом выхода 0.  Используется для создания условий, которые всегда будут истинными, или в качестве команды-пустышки.

6.  if test -f man$s  / $ i.$ s: Проверяет, существует ли файл с именем man$s/$i.$ s и является ли он обычным файлом.
    *   -f:  Оператор test, проверяющий, является ли указанный путь файлом.
    *   man$ s/ $i.$s:  Путь к файлу, где $s и $i – переменные, значения которых подставляются.  Предположительно, ищется файл справки man page.

7.  while vs until:
    *   while:  Выполняет команды *пока* условие истинно.
    *   until:  Выполняет команды *пока* условие ложно.

