---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №3"
subtitle: "Дисциплина: Операционные системы"
author: "Ездаков Егор Андреевич"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Изучить идеологию и применение средств контроля версий

# Задание

Сделайте отчёт по предыдущей лабораторной работе в формате Markdown. В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md


# Выполнение лабораторной работы

1. Создал учетную запись на GitHub (рис. -@fig:001).

![Создание учётной записи](screenshots/1.png){ #fig:001 }

2. Настроил систему контроля версий git (рис. -@fig:002, рис. -@fig:003)

Сгенерировал ssh-ключ:

![Создание нового ssh ключа](screenshots/2.png){ #fig:002 }

Добавил его в настройках учетной записи на GitHub

![Добавление ssh ключа на github](screenshots/3.png){ #fig:003 }

3. Создал структуру каталога лабораторных работ с помощью mkdir (рис. -@fig:004)

![Создание каталога](screenshots/4.png){ #fig:004 }

4. Создал репозиторий на GitHub. Назвал его os-intro (рис. -@fig:005):

![Создание репозитория](screenshots/5.png){ #fig:005 }

5. Перешёл в каталог laboratory: cd

6. Инициализировал системы git (рис. -@fig:006):

![Инициализация систем git](screenshots/6.png){ #fig:006 }

7. Создал заготовку для файла README.md (рис. -@fig:007):

![Создание заготовки для файла README.md](screenshots/7.png){ #fig:007 }

8. Создал первый коммит и отправил его на GitHub (рис. -@fig:008, рис. -@fig:009):

![Первый коммит](screenshots/8.jpg){ #fig:008 }

![Первый коммит](screenshots/9.jpg){ #fig:009 }

9. Добавил файл лицензии (рис. -@fig:010):

![Файл лицензии](screenshots/10.png){ #fig:010 }

10. Просмотрел список имеющихся шаблонов игнорируемых файлов (рис. -@fig:011):

![Список шаблонов игнорируемых файлов](screenshots/11.png){ #fig:011 }

11. Загрузил шаблон для С (рис. -@fig:012):

![Загрузка шаблона для С](screenshots/12.png){ #fig:012 }

12. Добавил новые файлы, отправил на GitHub (рис. -@fig:013, рис. -@fig:014):

![Добавление файлов на GitHub](screenshots/13.png){ #fig:013 }

![Добавление файлов на GitHub](screenshots/14.png){ #fig:014 }

13. Инициализировал git-flow (рис. -@fig:015):

![Инициализация git-flow](screenshots/15.png){ #fig:015 }

14. Префикс для ярлыков установил в v (рис. -@fig:016):

![Установка префикса](screenshots/16.png){ #fig:016 }

15. Находясь на ветке develop, создал релиз с версией 1.0.0 (рис. -@fig:017, рис. -@fig:018):

![Создание релиза](screenshots/17.png){ #fig:017 }

![Создание релиза](screenshots/18.png){ #fig:018 }

16. Записал версию (рис. -@fig:019):

![Запись версии](screenshots/19.png){ #fig:019 }

17. Добавил в индекс (рис. -@fig:020):

![Добавление в индекс](screenshots/20.png){ #fig:020 }

18. Залил релизную ветку в основную ветку (рис. -@fig:021):

![Залив релизной ветки](screenshots/21.png){ #fig:021 }

19. Отправил данные на GitHub (рис. -@fig:022):

![Отправка данных на GitHub](screenshots/23.png){ #fig:022 }

20. Создаем релиз на github. Для этого заходим в «Releases», нажимаем «Создать
новый релиз». Заходим в теги и заполняем все поля (создаём теги для версии 1.0.0).
После создания тега, автоматически сформируется релиз (рис. -@fig:023).

![Создание релиза](screenshots/22.png){ #fig:023 }

# Выводы

Я изучил идеологию и применение контроля версий.
