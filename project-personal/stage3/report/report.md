---
## Front matter
title: "Индивидуальный проект. 3 этап."
author: "Сарасбати Брасалес"

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

Добавить информацию о навыках, опыте и достижениях. Выложить два поста.


# Задание

Список достижений.
        Добавить информацию о навыках (Skills).
        Добавить информацию об опыте (Experience).
        Добавить информацию о достижениях (Accomplishments).
Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору:
        Легковесные языки разметки.
        Языки разметки. LaTeX.
        Язык разметки Markdown.


# Выполнение лабораторной работы

я перешла к созданию постов. Вначале я создала папки для этих постов.

![](image/WhatsApp Image 2023-04-08 at 21.02.48.jpeg){#fig:001 width=70%}

Я вставила заоранее подготовленный пост о прошедшей неделе.

![](image/WhatsApp Image 2023-04-08 at 21.04.01.jpeg){#fig:001 width=70%}

Я сделала то же самое для поста Markdown

![](image/WhatsApp Image 2023-04-08 at 21.05.09.jpeg){#fig:001 width=70%}

После я перешла в blog, открыла папку в терминале и набрада команду hugo.

![](image/WhatsApp Image 2023-04-08 at 21.05.49.jpeg){#fig:001 width=70%}

Затем я зашла в blog, открыл папку в терминале и набрал Hugo.

![](image/WhatsApp Image 2023-04-08 at 21.06.23.jpeg){#fig:001 width=70%}

Далее перешла в папку public, открыда ее в терминале и набрада три стандартные команды

![](image/WhatsApp Image 2023-04-08 at 21.07.11.jpeg){#fig:001 width=70%}

Я сделал то же самое в папке "blog"

![](image/WhatsApp Image 2023-04-08 at 21.07.36.jpeg){#fig:001 width=70%}

![](image/WhatsApp Image 2023-04-08 at 22.12.49.jpeg){#fig:001 width=70%}


# Выводы

Мы изменили информацию о навыках, достижениях и опыте и добавили новые посты.

# Список литературы{.unnumbered}

::: {#refs}
:::
