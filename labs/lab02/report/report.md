---
## Front matter
title: "Лабораторная работа №7"
subtitle: "Отчет"
author: "Ворожейкин Владимир Вячеславович"

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

Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. 

# Задание

Использовать команды для работы с файлами и каталогами;
Использовать перемещение и переименование файлов и каталогов;
Научиться настраивать права доступа;

# Выполнение лабораторной работы

Создаю файл abc1 и просматриваю его (рис.[-@fig:001]):

 ![Создание файла](image/1.png){#fig:001 width=70% height=70%}

 Копирую файл abc1 в файл april и в файл may (рис.[-@fig:002]):

 ![Копирование файла](image/2.png){#fig:002 width=70% height=70%}

 Копирую файлы april и may в каталог monthly (рис.[-@fig:003]):
 
 ![Копирование файла в каталог](image/3.png){#fig:003 width=70% height=70%}
 
 Копирую файл monthly/may в файл с именем june (рис.[-@fig:004]):
 
 ![Копирование файла в другой файл](image/4.png){#fig:004 width=70% height=70%}
 
  Копирую каталог monthly в каталог monthly.00 (рис.[-@fig:005]):
  
 ![Копирование файла в текущий каталог](image/5.png){#fig:005 width=70% height=70%}
 
 Копирую каталог monthly.00 в каталог /tmp (рис.[-@fig:006]):
 
 ![Копирование файла в другой каталог](image/6.png){#fig:006 width=70% height=70%}
 
 Изменяю название файла april на july в домашнем каталоге (рис.[-@fig:007]):
 
 ![Замена имени файла](image/7.png){#fig:007 width=70% height=70%}
 
 Перемещаю файл july в каталог monthly.00 (рис.[-@fig:008]):
 
 ![Перемещение файла в другой каталог](image/8.png){#fig:008 width=70% height=70%}
 
 Переименовать каталог monthly.00 в monthly.01 (рис.[-@fig:009]):
 
 ![Переименовывание каталога](image/9.png){#fig:009 width=70% height=70%}
 
 Перемещаю каталог monthly.01 в каталог reports (рис.[-@fig:010]):
 
 ![Перемещение каталога](image/10.png){#fig:010 width=70% height=70%}
 
 Переименовываю каталог reports/monthly.01 в reports/monthly (рис.[-@fig:011]):
 
 ![Переименовывание каталога, не являющегося текущим](image/11.png){#fig:011 width=70% height=70%}
 
 Создаю файл may с правом выполнения для владельца (рис.[-@fig:012]):
 
 ![Создание файла](image/12.png){#fig:012 width=70% height=70%}
 
 Лишаю владельца файла may права на выполнение (рис.[-@fig:013]):
 
 ![Лишение права](image/13.png){#fig:013 width=70% height=70%}
 
 Создаю каталог monthly с запретом на чтение для членов группы и всех остальных пользователей (рис.[-@fig:014]):
 
 ![Создание каталога](image/14.png){#fig:014 width=70% height=70%}
 
 Запрет на чтение (рис.[-@fig:015]):
 
 ![Запрет](image/15.png){#fig:015 width=70% height=70%}
 
 Создаю файл abc1 с правом записи для членов группы (рис.[-@fig:016]):
 
 ![Создание файла](image/16.png){#fig:016 width=70% height=70%}
 
 Копирую файл io.h и переименовываю его в equipment (рис.[-@fig:017]):
 
 ![Копирование и переименовывание файла](image/17.png){#fig:017 width=70% height=70%}
 
 Создаю директорию ~/ski.plases (рис.[-@fig:018]):
 
 ![Создание директории](image/18.png){#fig:018 width=70% height=70%}
 
 Проверяю содержимое директории (рис.[-@fig:019]):
 
 ![Проверка директории](image/19.png){#fig:019 width=70% height=70%}
 
 Создаю в домашнем каталоге файл abc1 и копирую его в каталог
~/ski.plases, называю его equiplist2 (рис.[-@fig:020]):

![Создание файла и его копирование](image/20.png){#fig:020 width=70% height=70%}

 Перемещаю файлы ski.plases/equiplist и equiplist2 в каталог ski.plases/equipment (рис.[-@fig:021]):
 
 ![Перемещение файлов](image/21.png){#fig:021 width=70% height=70%}
 
 Создаю и перемещаю каталог ~/newdir в каталог ~/ski.plases и называю
его plans (рис.[-@fig:022]):

![Создание каталога](image/22.png){#fig:022 width=70% height=70%}

Создаю необходимые директории и файлы (рис.[-@fig:023]):

![Создание директорий и файлов](image/23.png){#fig:023 width=70% height=70%}

Определяю опции команды chmod, необходимые для того, чтобы присвоить перечисленным ниже файлам выделенные права доступа (рис.[-@fig:024]):

![Создание директорий и файлов](image/24.png){#fig:024 width=70% height=70%}

Просматриваю содержимое файла etc/passwd (рис.[-@fig:025]):

![Файл passwd](image/25.png){#fig:025 width=70% height=70%}

Копирую файл feathers в файл file.old (рис.[-@fig:026]):

![Копирование файла](image/26.png){#fig:026 width=70% height=70%}

Перемещаю файл file.old в каталог play. Копирую каталог play в каталог fun (рис.[-@fig:027]):

![Выполнение пунктов 4.3 и 4.4](image/27.png){#fig:027 width=70% height=70%}

Перемещаю каталог fun в каталог play и называю его games. Лишаю владельца файла feathers права на чтение (рис.[-@fig:028]):

![Выполнение пунктов 4.5 и 4.6](image/28.png){#fig:028 width=70% height=70%}

Лишаю владельца каталога play права на чтение (рис.[-@fig:029]):

![Лишение права на чтение](image/29.png){#fig:029 width=70% height=70%}

Даю владельцу каталога play право на выполнение (рис.[-@fig:030]):

![Предоставление права на выполнение](image/30.png){#fig:030 width=70% height=70%}

Читаю man по командам mount, fsck, mkfs, kill (рис.[-@fig:031]):

![Чтение по командам](image/31.png){#fig:031 width=70% height=70%}

# Выводы

Во время выполнения данной лабораторной работы я приобрел практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами, по проверке использования диска и обслуживанию файловой системы.

# Список литературы{.unnumbered}

::: https://esystem.rudn.ru/pluginfile.php/2288520/mod_resource/content/4/005-lab_files.pdf
