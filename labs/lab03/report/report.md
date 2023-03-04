---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Markdown"
author: "Оганнисян Д.Б."

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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

Сделать отчёт по предыдущей лабораторной работе в формате Markdown.

# Теоретическое введение

Markdown — это облегченный язык разметки с синтаксисом форматирования обычного текста. созданный Джоном Грубером и Аароном Шварцем в 2004 году, сегодня это один из самых популярных языков среди программистов. Для записи Markdown можно использовать любой текстовый редактор. Смысл маркдауна в том, что вы делаете разметку своего документа минимальными усилиями, а уже какой-то другой плагин или программа превращает вашу разметку в итоговый документ — например в HTML. Но можно и не в HTML, а в PDF или что-нибудь ещё. [@mark:bash]

# Выполнение лабораторной работы

1.Установка git (рис. @fig:001).

![Установка git-flow в Fedora Linux](image/1.png){ #fig:001 width=70%} 

2.Установка gh (рис. @fig:002).

![Установка gh в Fedora Linux](image/2.png){ #fig:002 width=70% }

3.Базовая настройка git (рис. @fig:003).

![Зададим имя и email владельца репозитория:](image/3.png){#fig:003 width=70%}

![Настроим utf-8 в выводе сообщений git:](image/4.png){#fig:004 width=70%}

![Зададим имя начальной ветки (будем называть её master):](image/5.png){#fig:005 width=70%}

![Параметр autocrlf:](image/6.png){#fig:006 width=70%}

![Параметр safecrlf:](image/7.png){#fig:007 width=70%}

4.Создайте ключи ssh (рис. @fig:008).

![по алгоритму rsa с ключём размером 4096 бит и по алгоритму ed25519:](image/8.png){#fig:008 width=70%}

5.Создайте ключи pgp (рис. @fig:009)

![Генерируем ключ](image/9.png){#fig:009 width=70%}

6.Добавление PGP ключа в GitHub (рис. @fig:010)

![Cкопируйте ваш сгенерированный PGP ключ в буфер обмена:](image/10.png){#fig:010 width=70%}

7.Настройка автоматических подписей коммитов git (рис. @fig:011)

![Используя введёный email, укажите Git применять его при подписи коммитов:](image/11.png){#fig:011 width=70%}

8.Создание репозитория курса на основе шаблона (рис. @fig:012)

![создание репозитория примет следующий вид:](image/12.png){#fig:012 width=70%}

9.Настройка каталога курса (рис. @fig:013)

![Перейдите в каталог курса:](image/13.png){#fig:013 width=70%}

![Удалите лишние файлы:](image/14.png){#fig:014 width=70%}

![Создайте необходимые каталоги:](image/15.png){#fig:015 width=70%}

![Отправьте файлы на сервер:](image/16.png){#fig:016 width=70%}

# Выводы

В процессе выполнения этой лабораторной работы я научился работать с языком разметки Markdown. Познакомился с базовым синтаксисом Mardown.

# Список литературы{.unnumbered}

::: {#refs}
:::
