---
## Front matter
title: "4 этап индивидуального проекта"
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

Добавить к сайту ссылки на научные и библиометрические ресурсы.

# Задание

1. Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
eLibrary : https://elibrary.ru/
Google Scholar : https://scholar.google.com/;
ORCID : https://orcid.org/;
Mendeley : https://www.mendeley.com/;
ResearchGate : https://www.researchgate.net/;
Academia.edu : https://www.academia.edu/;
arXiv : https://arxiv.org/;
github : https://github.com/.
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору:
Оформление отчёта.
Создание презентаций.
Работа с библиографией.

# Выполнение лабораторной работы

Я открыла файл из папки work/solo/content/authors/admin. В файле мы изменили ссылки, я изменила ссылку Github и добавила ссылку Youtube, также я убрала лишние ссылки(рис. @fig:001).

![](image/WhatsApp Image 2023-04-28 at 21.41.47.jpeg){#fig:001 width=70%}

![](image/WhatsApp Image 2023-04-28 at 21.46.45.jpeg){#fig:002 width=70%}

После я создала папки для постов. 

![](image/WhatsApp Image 2023-04-28 at 21.47.26.jpeg){#fig:003 width=70%}

В файл "week" добавила информацию о прошедшей неделе.

![](image/WhatsApp Image 2023-04-28 at 21.52.37.jpeg){#fig:004 width=70%}

Во второй пост "отчет" добавила информацию об отчетах.

![](image/WhatsApp Image 2023-04-28 at 21.54.11.jpeg){#fig:005 width=70%}

![](image/WhatsApp Image 2023-04-28 at 21.55.01.jpeg){#fig:006 width=70%}

# Выводы

Мы разместили ссылки на научные и библиометрические ресурсы на сайте и выложили два поста.

# Список литературы{.unnumbered}

::: {#refs}
:::
