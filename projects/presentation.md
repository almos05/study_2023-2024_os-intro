---
## Front matter
lang: ru-RU
title: Индивидуальный проект
subtitle: Презентация
author:
  - Мосолов А.Д.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 02 марта 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'

## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
---

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Мосолов Александр Денисович
  * Студент, НПИбд02-23
  * Российский университет дружбы народов
  * [1132236128@pfur.ru](mailto:1132236128@pfur.ru)

:::
::: {.column width="30%"}

:::
::::::::::::::

## Цель работы


Изучить способы размещения своего сайта на хостинге, используя генератор статических сайтов Hugo и Github.

## Задание


Установить необходимое программное обеспечение.  
Скачать шаблон темы сайта.  
Разместить его на хостинге git.  
Установить параметр для URLs сайта.  
Разместить заготовку сайта на Github pages.

## Установка go

Установим язык golang

![Установка go](image/image-1.png)

## Скачиваем Hugo

Перейдем на Github, который содержит релизы Hugo, скачаем версию для linux-amd64

![Скачиваем Hugo](image/image-2.png)

## Распаковка Hugo

Распакуем скачанный файл

![Распаковка Hugo](image/image-3.png){height=50%}

## Перенесём hugo

Перенесём hugo в /usr/local/bin/

![Перенесём hugo](image/image-4.png)

## Проверка

Проверяем перенёсся ли файл

![Проверка](image/image-5.png)

Переходим по ссылке https://github.com/HugoBlox/theme-academic-cv скопируем себе в github этот template, назовём его myblog

## Копируем репозиторий

![Копируем репозиторий](image/image-6.png)

Клонируем в него

## Клон в myblog

![Клон в myblog](image/image-7.png)

## Запуск локального сервера

Перейдем в myblog и запустим сервер, используя команду hugo server

![Запуск локального сервера](image/image-8.png)

## Адрес локального сервера

Используя адрес локального сервера мы можем запустить его у себя на компьютере

![Адрес локального сервера](image/image-9.png)

## Создание нового репозитория

Создаём новый пустой репозиторий

![Создание нового репозитория](image/image-10.png)

## Клон в almos05.github.io

Клонируем в него

![Клон в almos05.github.io](image/image-11.png)

## Переключаемся на новую ветку main

Переключаемся на новую ветку main

![Переключаемся на новую ветку main](image/image-12.png)

## Создание файла README.md

Создаем файл README.md

![Создание файла README.md](image/image-13.png)

## Commit README.md

Фиксируем изменения

![Commit README.md](image/image-14.png)

## Подгружаем на Gihub

Подгружаем на Gihub

![Подгружаем на Gihub](image/image-15.png)

## Комментируем public

Комментируем public в файле .gitignore

![Комментируем public](image/image-16.png)

## Удаляем public

Переходим в myblog, удаляем public

![Удаляем public](image/image-17.png)

## Делаем submodule

Делаем submodule

![Делаем submodule](image/image-18.png)

## Запуск сервера

Запускаем hugo server

![Запуск сервера](image/image-19.png)

## Грузим на github изменения

Фиксируем изменения на github  
*git add .*  
*git commit -am 'make project-1'*  
*git push origin main*   

Теперь наш сайт находится по ссылке:  
https://almos05.github.io/

![Грузим на github изменения](image/image-20.png){height=30%}

## Выводы

В ходе работы мы изучили способы размещения своего сайта на хостинге, используя генератор статических сайтов Hugo и Github.
