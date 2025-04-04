---
## Front matter
title: "Отчет по второму этапу индивидуального проекта"
subtitle: "Операционные системы"
author: "Барето Вилиан Мануел"

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

Продолжить работы со своим сайтом. Редактировать его в соответствии с требованиями. Добавить данные о себе.

# Задание

1. Разместить фотографию владельца сайта.
2. Разместить краткое описание владельца сайта (Biography).
3. Добавить информацию об интересах (Interests).
4. Добавить информацию от образовании (Education).
5. Сделать пост по прошедшей неделе.
6. Добавить пост на тему управление версиями. Git.

# Выполнение лабораторной работы

Добавила свою фотографию в папку blog/content/authors/admin, удалила фотографию шаблона 

![Добавление фотографии](image/1.png){#fig:001 width=70%}

В файлу index.md в той же папке изменяю поля. Начинаю с библиографии

![Запись библиографии](image/2.png){#fig:002 width=70%}

Изменила интересы на свои

![Запись интересов](image/3.png){#fig:003 width=70%}

Добавила свое образование

![Запись образования](image/4.png){#fig:004 width=70%}

Обновила личные данные, чтобы они были про меня 

![Обновление личных данных](image/5.png){#fig:005 width=70%}

Создаю папки в директории post, которые обозначают посты и в которых будут тексты постов, картинки и доп. файлы

![Создание папок-постов](image/6.png){#fig:006 width=70%}

Заполнила файл index.md в post1, это пост про прошедшую неделю 

![Пост про прошедшую неделю](image/7.png){#fig:007 width=70%}

Заполнила файл index.md в post2, это пост про управление версиями Git 

![Пост на конкретную тему](image/8.png){#fig:008 width=70%}

Закрываю локальный сервер. Генерирую сайт с изменениями 

![Генерация сайта](image/9.png){#fig:009 width=70%}

Сохраняю изменения на гите

![Сохранение на гите](image/10.png){#fig:010 width=70%}

# Выводы

В процессе выполнения второго этапа индивидуального проекта я научилась редактировать данные о себе, а также писать посты и добавлять их на сайт.

# Список литературы{.unnumbered}

::: {#refs}
:::
