---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Дисциплина: архитектура компьютера"
author: "Елизавета Александровна Киселева"

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

Целью данной лабораторной работы является освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown

# Задание

1. Заполнение отчета по выполнению лабораторной работы №2 с помощью языка разметки Markdown
2. Задание для самостоятельной работы

# Теоретическое введение

Markdown - легковесный язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций. 
Внутритекстовые формулы делаются аналогично формулам LaTeX.
В Markdown вставить изображение в документ можно с помощью непосредственного указания адреса изображения.
Синтаксис Markdown для встроенной ссылки состоит из части [link text], представляющей текст гиперссылки, и части (file-name.md) – URL-адреса или имени файла, на который дается ссылка.
Markdown поддерживает как встраивание фрагментов кода в предложение, так и их размещение между предложениями в виде отдельных огражденных блоков. Огражденные блоки кода — это простой способ выделить синтаксис для фрагментов кода.

# Выполнение лабораторной работы

## Заполнение отчета по выполнению лабораторной работы №2 с помощью языка разметки Markdown

Открываю терминал. Перехожу в каталог курса, сформированный при выполненнии прошлой лаборатной работы и обновляю локальный репозиторий, скачав изменения из удаленного репозитория с помощью команды git pull (рис. [-@fig:001]).

![Перемещение и обновление](image/1.jpg){#fig:001 width=70%}

Компилирую шаблон с использованием Makefile, вводя команду make (рис. [-@fig:002]).

![Компиляция шаблона](image/1.jpg){#fig:002 width=70%}

Удаляю полученные файлы с использованием Makefile, вводя команду make clean (рис. [-@fig:003]).

![Удаление файлов](image/1.jpg){#fig:003 width=70%}

Открываю файл report.md с помощью текстового редактора командой gedit (рис. [-@fig:004]).

![Открытие файла](image/1.jpg){#fig:004 width=70%}

Начинаю заполнять отчет с помощью языка разметки Markdown в скопированном файле (рис. [-@fig:005]).

![Заполнение отчёта](image/2.png){#fig:005 width=70%}

Далее компилирую файл с отчетом. Загружаю отчет на GitHub (рис. [-@fig:006]).
(Не могу скомпелировать, грузится уже больше часа).

![Компиляция и отправка](image/3.png){#fig:006 width=70%}

## Задание для самостоятельной работы

1. Перехожу в директорию lab03/report с помощью cd, чтобы там заполнять отчет по третьей лабораторной работе (рис. [-@fig:007]).

![Перемещение между директориями](image/5.png){ #fig:007 width=70% }

Открываю файл с помощью текстового редактора gedit и начинаю заполнять отчет (рис. [-@fig:008]).

![Работа над отчетом](image/4.png){ #fig:008 width=70% }

Компилирую файл с отчетом по лабораторной работе.Добавляю изменения на GitHub с помощью комнадой git add и сохраняю изменения с помощью commit, отправлялю файлы на сервер с помощью команды git pull ([-@fig:010]). 
(Также не могу доконца скомпелировать)


# Выводы

В результате выполнения данной лабораторной работы я освоила процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Список литературы{.unnumbered}

1. [Архитектура ЭВМ](https://esystem.rudn.ru/pluginfile.php/1584625/mod_resource/content/1/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%E2%84%964.pdf)
