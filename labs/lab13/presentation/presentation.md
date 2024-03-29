---
## Front matter
lang: ru-RU
title: Лабораторная работа No 13.
subtitle: Средства, применяемые при разработке программного обеспечения в ОС типа UNIX/Linux
author:
  - Сарасбати Брасалес
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 05/05/2023

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
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Сарасбати Брасалес
  * Российский университет дружбы народов
  * [sarasbati2904s@gmail.com](sarasbati2904s@gmail.com)

:::
::: {.column width="30%"}



:::
::::::::::::::

# Вводная часть

## Цель

Приобрести простейшие навыки разработки, анализа, тестирования и отладки при-
ложений в ОС типа UNIX/Linux на примере создания на языке программирования
С калькулятора с простейшими функциями.

## Задание

1. В домашнем каталоге создайте подкаталог ~/work/os/lab_prog.

2. Создайте в нём файлы: calculate.h, calculate.c, main.c. Это будет примитивнейший калькулятор, способный складывать, вычитать, умножать и делить, возводить число в степень, брать квадратный корень, вычислять sin, cos, tan. При запуске он будет запрашивать первое число, операцию, второе число. После этого программа выведет результат и остановится.

3. Выполните компиляцию программы посредством gcc

##  Задание

4. При необходимости исправьте синтаксические ошибки.

5. Создайте Makefile со следующим содержанием.

6. С помощью gdb выполните отладку программы calcul (перед использованием gdb исправьте Makefile)

7. С помощью утилиты splint попробуйте проанализировать коды файлов calculate.c и main.c.

# Выполнение лабораторной работы

## Создание каталогов и файлов

![](image/WhatsApp Image 2023-05-05 at 20.38.31.jpeg)

## Компиляция программы

![](image/WhatsApp Image 2023-05-05 at 20.40.05.jpeg)

## Makefile

![](image/WhatsApp Image 2023-05-05 at 20.41.18.jpeg)

## Запуск отладчика

![](image/WhatsApp Image 2023-05-05 at 20.43.18.jpeg)

## Запуск программы

![](image/WhatsApp Image 2023-05-05 at 20.44.14.jpeg)

## Просмотр исходного кода

![](image/WhatsApp Image 2023-05-05 at 20.46.13.jpeg)

## Breakpoints

![](image/WhatsApp Image 2023-05-05 at 20.47.19.jpeg)

## splint

![](image/WhatsApp Image 2023-05-05 at 20.48.08.jpeg)

# Выводы

## Вывод

Мы приобрели простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

## Код для формата `pdf`

```yaml
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
```

## Код для формата `html`

- Тема задаётся в файле `Makefile`

```make
REVEALJS_THEME = beige 
```

## Связь слайдов

::: incremental

- Один слайд --- одна мысль
- Нельзя ссылаться на объекты, находящиеся на предыдущих слайдах (например, на формулы)
- Каждый слайд должен иметь заголовок

:::

## Количество сущностей

::: incremental

- Человек может одновременно помнить $7 \pm 2$ элемента
- При размещении информации на слайде старайтесь чтобы в сумме слайд содержал не более 5 элементов
- Можно группировать элементы так, чтобы визуально было не более 5 групп

:::

## Общие рекомендации

::: incremental

- На слайд выносится та информация, которая без зрительной опоры воспринимается хуже
- Слайды должны дополнять или обобщать содержание выступления или его частей, а не дублировать его
- Информация на слайдах должна быть изложена кратко, чётко и хорошо структурирована
- Слайд не должен быть перегружен графическими изображениями и текстом
- Не злоупотребляйте анимацией и переходами

:::

## Представление данных

::: incremental

- Лучше представить в виде схемы
- Менее оптимально представить в виде рисунка, графика, таблицы
- Текст используется, если все предыдущие способы отображения информации не подошли

:::

