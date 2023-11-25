## Front matter
title: "Лабораторная работа 6"
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

Изучить в Octave методы расчета пределов, частичных сумм, суммы ряда, а также методы вычисления интегралов и аппроксимирования суммами.

# Теоретическое введение

Анонимная функция - особый вид функций, которые объявляются в месте использования и не получают уникального идентификатора для доступа к ним. Обычно при создании анонимные функции либо вызываются напрямую, либо ссылка на функцию присваивается переменной, с помощью которой затем можно косвенно вызывать данную функцию.

В Octave aнонимные функции определяются с помощью синтаксиса @(argument-list) expression. Любые переменные, которые не найдены в списке аргументов, наследованы от объема включения. Анонимные функции полезны для создания простых функций без имени от выражений или для обертывания вызовов к другим функциям для адаптации их к использованию функциями как quad, которая применяется при вычислении интегралов.

# Выполнение лабораторной работы



Оценка выражения под знаком предела

![Оценка выражения под знаком предела](image/Pic 1.jpg){#fig:001 width=80%}

![Оценка выражения под знаком предела](image/Pic 2.jpg){#fig:002 width=80%}

Частичные суммы

![Частичные суммы](image/Pic 3.jpg){#fig:003 width=110%}


 
 Сумма ряда
.

![Сумма ряда](image/Pic 4.jpg){#fig:004 width=40%}


 Вычисление интеграла
 
.

![Вычисление интеграла](image/Pic 5.jpg){#fig:005 width=80%}

Аппроксимирование суммами

![Аппроксимирование суммами](image/Pic 6.jpg){#fig:006 width=80%}

Аппроксимирование суммами2

![Аппроксимирование суммами2](image/Pic 7.jpg){#fig:007 width=60%}

Сравнение кодов

![Сравнение кодов](image/Pic 10.jpg){#fig:010 width=80%}

# Выводы

В ходе выполнения данной лабораторной работы я изучил в Octave методы расчета пределов, частичных сумм, суммы ряда, а также методы вычисления интегралов и аппроксимирования суммами.



# Список литературы{.unnumbered}

::: {#refs}
:::
