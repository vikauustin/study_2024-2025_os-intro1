---
## Front matter
title: "Лаборатораня работа №5"
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

Научится настраивать рабочую среду.

# Задание

Менеджер паролей pass
Настройка интерфейса с броузером
Сохранение пароля
Дополнительное программное обеспечение
Создание собственного репозитория с помощью утилит
Подключение репозитория к своей системе
Использование chezmoi на нескольких машинах
Настройка новой машины с помощью одной команды
Ежедневные операции c chezmoi

# Выполнение лабораторной работы

Устанавливаем менеджер паролей pass(рис. [-@fig:001]).

![Процесс установки](image/1.jpg){#fig:001 width=70%}

Устанавливаем менеджер паролей pass следубщая команда(рис. [-@fig:002]).

![Процесс установки](image/2.jpg){#fig:002 width=70%}

Просмотр списка ключей и инициализируем хранилище(рис. [-@fig:003]).

![Наш ключ почта, инициализируем хранилище](image/3.jpg){#fig:003 width=70%}

Предварительно создаем репозиторий pass и нужно задать адрес репозитория на хостинге, выполняем комнаду pass git pull(рис. [-@fig:004]).

![Задаем адрес,создаем репозиторий](image/4.jpg){#fig:004 width=70%}

Для синхронизации выполняется следующая команда(рис. [-@fig:005]).

![вводим команду](image/5.jpg){#fig:005 width=70%}

Переходим в cd ~/.password-store/ и необходимо вручную закоммитить и выложить изменения(рис. [-@fig:006]).

![Вводим команды из туиса](image/6.jpg){#fig:006 width=70%}

Кроме плагина к броузеру устанавливается программа, обеспечивающая интерфейс native messaging.(рис. [-@fig:007]).

![Для федоры устанавливаем так, как сказано, и качаем файл дополнительный на машину](image/7.jpg){#fig:007 width=70%}

Создаем новый файл, и устанавливаем для него пароль(рис. [-@fig:008]).

![Установили новый пароль](image/8.jpg){#fig:008 width=70%}

Отобразите пароль для указанного имени файла и замените существующий пароль(рис. [-@fig:009]).

![Пароль отобразился и мы его заменили на тот, что желтым цветом](image/9.jpg){#fig:009 width=70%}

Установите дополнительное программное обеспечение(рис. [-@fig:010]).

![Устанавливаем много пакетов](image/10.jpg){#fig:010 width=70%}

Установите шрифты(рис. [-@fig:011]).

![Занимаемся процессом установки нужных шрифтов](image/11.jpg){#fig:011 width=70%}

Установка бинарного файла, создание репозитория для конфигурационных файлов и инициализируйте chezmoi с моим репозиторием dotfiles(рис. [-@fig:012]).

![Устанавливаем файл и переносим его, чтобы инициализировать](image/12.jpg){#fig:012 width=70%}

Проверьте, какие изменения внесёт chezmoi в домашний каталог(рис. [-@fig:013]).

![Много изменений, все не влезло](image/13.jpg){#fig:013 width=70%}

Можно установить свои dotfiles на новый компьютер с помощью одной команды(рис. [-@fig:014]).

![Переходим в федору воркстейшн и устанавливаем](image/14.jpg){#fig:014 width=70%}

Можно извлечь изменения из репозитория и применить их одной командой, и извлеките последние изменения из своего репозитория (рис. [-@fig:015]).

![У нас все актуально, так же мы написали функцию для автоматического отправки изменений в репозиторий](image/15.jpg){#fig:015 width=70%}

# Выводы

У нас получилось настроить рабочую среду.

