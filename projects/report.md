---
## Front matter
title: "Индивидуальный проект"
subtitle: "Стадия 1"
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


Изучить способы размещения своего сайта на хостинге, используя генератор статических сайтов Hugo и Github.[@TUIS]

# Задание


Установить необходимое программное обеспечение.  
Скачать шаблон темы сайта.  
Разместить его на хостинге git.  
Установить параметр для URLs сайта.  
Разместить заготовку сайта на Github pages.


# Выполнение лабораторной работы

Установим язык golang (рис. [-@fig:001]):

![Установка go](image/image-1.png){#fig:001 width=70%}

Перейдем на Github, который содержит релизы Hugo, скачаем версию для linux-amd64 (рис. [-@fig:002]):

![Скачиваем Hugo](image/image-2.png){#fig:002 width=70%}

Распакуем скачанный файл (рис. [-@fig:003]):

![Распаковка Hugo](image/image-3.png){#fig:003 width=70%}

Перенесём hugo в /usr/local/bin/ (рис. [-@fig:004]):

![Перенесём hugo](image/image-4.png){#fig:004 width=70%}

Проверяем перенёсся ли файл (рис. [-@fig:005]):

![Проверка](image/image-5.png){#fig:005 width=70%}

Переходим по ссылке https://github.com/HugoBlox/theme-academic-cv скопируем себе в github этот template, назовём его myblog (рис. [-@fig:006]):

![Копируем репозиторий](image/image-6.png){#fig:006 width=70%}

Клонируем в него (рис. [-@fig:007]):

![Клон в myblog](image/image-7.png){#fig:007 width=70%}

Перейдем в myblog и запустим сервер, используя команду hugo server (рис. [-@fig:008]):

![Запуск локального сервера](image/image-8.png){#fig:008 width=70%}


Используя адрес локального сервера мы можем запустить его у себя на компьютере (рис. [-@fig:009]):

![Адрес локального сервера](image/image-9.png){#fig:009 width=70%}

Создаём новый пустой репозиторий (рис. [-@fig:010]):

![Создание нового репозитория](image/image-10.png){#fig:010 width=70%}

Клонируем в него (рис. [-@fig:011]):

![Клон в almos05.github.io](image/image-11.png){#fig:011 width=70%}

Переключаемся на новую ветку main (рис. [-@fig:012]):

![Переключаемся на новую ветку main](image/image-12.png){#fig:012 width=70%}

Создаем файл README.md (рис. [-@fig:013]):

![Создание файла README.md](image/image-13.png){#fig:013 width=70%}

Фиксируем изменения (рис. [-@fig:014]):

![Commit README.md](image/image-14.png){#fig:014 width=70%}

Подгружаем на Gihub (рис. [-@fig:015]):

![Подгружаем на Gihub](image/image-15.png){#fig:015 width=70%}

Комментируем public в файле .gitignore (рис. [-@fig:016]):

![Комментируем public](image/image-16.png){#fig:016 width=70%}

Переходим в myblog, удаляем public (рис. [-@fig:017]):

![Удаляем public](image/image-17.png){#fig:017 width=70%}

Делаем submodule (рис. [-@fig:018]):

![Делаем submodule](image/image-18.png){#fig:018 width=70%}

Запускаем hugo server (рис. [-@fig:019]):

![Запуск сервера](image/image-19.png){#fig:019 width=70%}

Фиксируем изменения на github (рис. [-@fig:020]):  
*git add .*  
*git commit -am 'make project-1'*  
*git push origin main*

![Грузим на github изменения](image/image-20.png){#fig:020 width=70%}

Теперь наш сайт находится по ссылке:  
https://almos05.github.io/

# Выводы

В ходе работы мы изучили способы размещения своего сайта на хостинге, используя генератор статических сайтов Hugo и Github.

# Список литературы{.unnumbered}

::: {#refs}
:::
