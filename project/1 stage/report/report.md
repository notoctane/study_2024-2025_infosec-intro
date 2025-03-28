---
## Front matter
title: "Отчет индивидуальному проекту. Этап 1"
subtitle: "Основы информационной безопасности"
author: "Наговицын Арсений, НКАбд-03-23"

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

# Задание

1. Создание и настройка виртуальной машины

2. Установка Kali linux


# Выполнение лабораторной работы

## Создание и настройка виртуальной машины

Создаю новую виртуальную машину (рис. @fig:001).

![Окно VirtualBox](image/1.png){#fig:001 width=70%}

Выделяю 10 ядер процессора (рис. @fig:002).

![Окно VirtualBox](image/2.png){#fig:002 width=70%}

Создаю новый виртуальный жесткий диск (рис. @fig:003).

![Окно VirtualBox](image/3.png){#fig:003 width=70%}

## Установка Kali linux

Выбираю язык, на котором будет система Kali Linux (рис. @fig:004).

![Установщик Kali Linux](image/4.png){#fig:004 width=70%}

Создаю пользователя (рис. @fig:005).

![Установщик Kali Linux](image/5.png){#fig:005 width=70%}

Создаю пароль для пользователя (рис. @fig:006).

![Установщик Kali Linux](image/6.png){#fig:006 width=70%}

Настраиваю разметку диска (рис. @fig:007).

![Установщик Kali Linux](image/7.png){#fig:007 width=70%}

Настройка разметки дисков (рис. @fig:008).

![Установщик Kali Linux](image/8.png){#fig:008 width=70%}

Установка GRUB (рис. @fig:009).

![Установщик Kali Linux](image/9.png){#fig:009 width=70%}

Завершение установки (рис. @fig:008).

![Установщик Kali Linux](image/8.png){#fig:008 width=70%}

# Выводы

В этом этапе проекта, я получил практические навыки в установке системы Kali Linux.

# Список литературы{.unnumbered}

::: {#refs}
:::
