---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Отчёт"
author: "Александр Денисович Мосолов"

## Generic otionsв
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown. [@TUIS]

# Задание

Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.
– В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.)

# Выполнение лабораторной работы

Вырезаем из скринкаста нужные скриншоты (рис. [-@fig:001]):

![Выбор скриншотов](image/image-1.png){#fig:001 width=70%}

Заполняем основные разделы, размещаем заголовки с помощью # (рис. [-@fig:002]):

![Размещаем заголовки](image/image-2.png){#fig:002 width=70%}

Предоставляем оформленную информацию со ссылкой на рисунки (рис. [-@fig:003]):

![Делаем ссылки](image/image-3.png){#fig:003 width=70%}

Описываем действия из туиса, размещаем фотографии к тексту (рис. [-@fig:004]):

![Синтаксис размещения фотографий](image/image-4.png){#fig:004 width=70%}

Заранее переименовываем фото, чтобы было удобнее заполнять поля (рис. [-@fig:005]):

![Переименновываем](image/image-5.png){#fig:005 width=70%}

Заполняем cite.bib файл, предоставляем информацию о курсе в ТУИС (рис. [-@fig:006]):

![Доп. литература](image/image-6.png){#fig:006 width=70%}

Делаем выводы и заканчиваем работу, создаем в папке с report.md файл типа docx и pdf с помощью команды make (рис. [-@fig:007]):

![Создаем make-файлы](image/image-7.png){#fig:007 width=70%}

Проверяем работу на ошибки (рис. [-@fig:08]):

![Проверка](image/image-8.png){#fig:08 width=70%}

Фиксируем изменения на github:
*git add .*  
*git commit -am 'feat(main): make lab03'*  
*git push* 

# Выводы

В ходе работы мы научились оформлять отчёты с помощью легковесного языка разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
