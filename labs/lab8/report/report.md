## Front matter
title: "Лабораторная работа 8"
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

Изучить в Octave методы работы с собственными значениями и собственными векторами, а также с марковскими цепями (случайное блуждание).

# Теоретическое введение

Система называется цепью Маркова, если последовательность случайных событий удовлетворяет следующим условиям:

1)возможно конечное число состояний,

2)через определенные промежутки времени проводится наблюдение и регистрируется состояние системы,

3)для каждого состояния задается вероятность перехода в каждое из остальных состояний или вероятность остаться в том же самом состоянии. Существенным предположением является то, что эти вероятности зависят только от текущего состояния.

# Выполнение лабораторной работы

Нахождение собственных значений и векторов матрицы
![Нахождение собственных значений и векторов матрицы](image/Pic 1.jpg)

Получение матрицы с действительными собственными значениями
![Получение матрицы с действительными собственными значениями](image/Pic 2.jpg)

Нахождение вектора вероятности после 5 шагов
![Нахождение вектора вероятности после 5 шагов](image/Pic 3.jpg)

Нахождение вектора вероятности после 5 шагов
![Нахождение вектора вероятности после 5 шагов](image/Pic 4.jpg)

Нахождение вектора равновесного состояния
![Нахождение вектора равновесного состояния](image/Pic 5.jpg)

Проверка результата
![Проверка результата](image/Pic 6.jpg){#fig:006 width=80%}


# Выводы

В ходе выполнения данной лабораторной работы я изучил в Octave методы работы с собственными значениями и собственными векторами, а также с марковскими цепями (случайное блуждание).



# Список литературы{.unnumbered}

::: {#refs}
:::

