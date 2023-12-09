## Front matter
title: "Лабораторная работа 7"
subtitle: "Научное программирование"
author: "Минов Кирилл Вячеславович | НПМмд-02-23"

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

Изучить в Octave методы построения различных графиков и работы с комплексными числами и специальными функциями.
Один из способов построения трехмерных графиков связан с использованием функции surf. Наиболее часто функция вызывается в формате surf(X,Y, Z) или в surf(X, Y, Z, С). X и Y - векторы-строки, определяющие значения абсцисс и ординат. Z - матрица с размерностью, равной произведению размерностей матриц X и Y, задающая значения координаты z для соответствующих пар х и у. Параметр С определяет способ отображения трехмерной картинки 
Гамма функция находит очень широкое применение в прикладном анализе. С гамма-функцией связаны функции Бесселя используемые при синтезе фильтров и спектральном анализе, а также другие специальные функции: бета-функция, К-функции, G-функции.

# Теоретическое введение

Основной функцией для построения двумерных графиков в Octave служит функция plot.

# Выполнение лабораторной работы



# Выводы


В ходе выполнения данной лабораторной работы я изучил в Octave методы построения различных графиков и работы с комплексными числами и специальными функциями.


# Список литературы{.unnumbered}

::: {#refs}
:::
