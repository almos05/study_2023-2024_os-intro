---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
subtitle: Презентация
author:
  - Мосолов А.Д.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 09 марта 2024

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

## Цель


Получение навыков правильной работы с репозиториями git.

## Задание


Выполнить работу для тестового репозитория.  
Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.

## Enable the copr repository

Установка из коллекции репозиториев Copr

![Enable the copr repository](image/image-1.png)

## Install gitflow

Установка gitflow

![Install gitflow](image/image-2.png)

## Установка Node.js

Установка Node.js

![Установка Node.js](image/image-3.png)

## Установка pnpm

Установка pnpm с помощью wget

![Установка pnpm](image/image-4.png)

## Запускаем pnpm

Запускаем pnpm и выполняем

![Запускаем pnpm](image/image-5.png)

## Клонируем репозиторий

Создаем пустой репозиторий и клонируем его

![Клонируем репозиторий](image/image-6.png)

## Standard-changelog

standard-changelog используется для помощи в создании логов

![Standard-changelog](image/image-7.png)

## Commitizen

Commitizen используется для помощи в форматировании коммитов

![Commitizen](image/image-8.png)

## Первый коммит

Создаем пустой файл README.md, фиксируем изменения и делаем первый коммит

![Первый коммит](image/image-9.png)

## git push в ветку main

Делаем git push в ветку main

![git push в ветку main](image/image-10.png)

## pnpm init

Конфигурация для пакетов Node.js

![pnpm init](image/image-11.png)

## Изменяем package.json

Изменяем package.json

![Изменяем package.json](image/image-12.png)

## Заливаем на гитхаб

Добавим новые файлы:  
git add .

Выполним коммит:  
git cz

Отправим на github:  
git push

## Инициализируем git-flow

Инициализируем git-flow, префикс для ярлыков установим в v

![Инициализируем git-flow](image/image-13.png)

## Ветка develop

Проверьте, что Вы на ветке develop

![Ветка develop](image/image-14.png)

## git push --all

Загружаем весь репозиторий в хранилище

![git push --all](image/image-15.png)

## Внешняя ветка становится вышестоящей

Установим внешнюю ветку как вышестоящую для этой ветки

![Внешняя ветка становится вышестоящей](image/image-16.png)

## Создадим релиз с версией 1.0.0

Создадим релиз с версией 1.0.0

![Создадим релиз с версией 1.0.0](image/image-17.png)

## Добавим журнал изменений в индекс

Создадим журнал изменений  
standard-changelog --first-release  
И добавим журнал изменений в индекс

![Добавим журнал изменений в индекс](image/image-18.png)

## Отправим данные на github

Зальём релизную ветку в основную ветку  
git flow release finish 1.0.0  
Отправим данные на github

![Отправим данные на github](image/image-20.png){height=50%}

## Создадим релиз на github

Создадим релиз на github. Для этого будем использовать утилиты работы с github

![Создадим релиз на github](image/image-21.png)

## Создадим ветку для новой функциональности

Создадим ветку для новой функциональности

![Создадим ветку для новой функциональности](image/image-22.png)

## Создадим релиз с версией 1.2.3

Создадим релиз с версией 1.2.3

![Создадим релиз с версией 1.2.3](image/image-23.png)

## Обновите номер версии в файле package.

Обновите номер версии в файле package.json. Установите её в 1.2.3

![Обновите номер версии в файле package.json](image/image-25.png)

## Создадим журнал изменений

Создадим журнал изменений

![Создадим журнал изменений](image/image-24.png)

## Добавим журнал изменений в индекс

Добавим журнал изменений в индекс  
git add CHANGELOG.md, сделаем новый коммит

![Добавим журнал изменений в индекс](image/image-26.png)

## Зальём релизную ветку в основную ветку

Зальём релизную ветку в основную ветку

![Зальём релизную ветку в основную ветку](image/image-27.png)

## Отправим данные на github

Отправим данные на github

![Отправим данные на github](image/image-28.png)

## Создадим релиз на github

Зальём релизную ветку в основную Создадим релиз на github с комментарием из журнала изменений]):

![Создадим релиз на github с комментарием из журнала изменений](image/image-29.png)

## Выводы

В ходе работы мы получили навыки правильной работы с репозиториями git.
