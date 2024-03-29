---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
subtitle: Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки
author:
  - Медникова Е.М.
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Факультет физико-математических и естественных наук
date: 4 марта 2023

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

  * Медникова Екатерина Михайловна
  * студентка направления бакалавриата 01.03.00 Математика и механика
  * Российский университет дружбы народов
  * [1132226549@rudn.ru](mailto:1132226549@rudn.ru)

:::
::: {.column width="30%"}

:::
::::::::::::::

# Цель работы

Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.

# Выполнение лабораторной работы

## Определила полное имя своего домашнего каталога.

![](./image/снимок1.png)

## Перешла в каталог /tmp.

![](./image/снимок2.1.png)

## Вывела на экран содержимое каталога /tmp.

![](./image/снимок2.2.png)

## Вывела на экран содержимое каталога /tmp.

![](./image/снимок2.2а.png)

## Вывела на экран содержимое каталога /tmp.

![](./image/снимок2.2б.png)

## Продолжение

Для того, чтобы отобразить имена скрытых файлов, необходимо использовать команду ls
с опцией a. Чтобы вывести на экран подробную информацию о файлах и каталогах, необходимо использовать опцию l. При этом о каждом файле и каталоге будет выведена следующая информация:
– тип файла,
– право доступа,
– число ссылок,
– владелец,
– размер,
– дата последней ревизии,
– имя файла или каталога.

## В каталоге /var/spool нет подкаталога с именем cron. 

![](./image/снимок2.3.png)

## Перешла в свой домашний каталог и вывела на экран его содержмиое.

![](./image/снимок2.4.png)

## В домашнем каталоге создала новый каталог с именем newdir.

![](./image/снимок3.12.png)

## В каталоге ~/newdir создала новый каталог с именем morefun.

![](./image/снимок3.12.png)

## В домашнем каталоге создала одной командой три новых каталога с именами letters, memos, misk. Затем удалила эти каталоги одной командой.

![](./image/снимок3.3.png)

## В домашнем каталоге создала одной командой три новых каталога с именами letters, memos, misk. Затем удалила эти каталоги одной командой.

![](./image/снимок3.3а.png)

## Попробовала удалить ранее созданный каталог ~/newdir командой rm. Проверила, был ли каталог удалён.

![](./image/снимок3.45.png)

## Удалила каталог ~/newdir/morefun из домашнего каталога. Проверила, был ли каталог удалён.

![](./image/снимок3.45.png)

## С помощью команды man определила, какую опцию команды ls нужно использовать для просмотра содержимого не только указанного каталога, но и подкаталогов, входящих в него.

![](./image/снимок4.png)

## С помощью команды man определила набор опций команды ls, позволяющий отсортировать по времени последнего изменения выводимый список содержимого каталога с развёрнутым описанием файлов.

![](./image/снимок5.png)

## Использовала команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm.

![](./image/снимок6.png)

## Использовала команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm.

![](./image/снимок6а.png)

## Использовала команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm.

![](./image/снимок6б.png)

## Использовала команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm.

![](./image/снимок6в.png)

## Использовала команду man для просмотра описания следующих команд: cd, pwd, mkdir, rmdir, rm.

![](./image/снимок6г.png)

## Продолжение

Команда cd используется для перемещения по файловой системе операционной системы типа Linux. Для определения абсолютного пути к текущему каталогу используется команда pwd.
Команда mkdir используется для создания каталогов. Команда rm используется для удаления файлов и/или каталогов. Для удаления пустового каталога используется команда rmdir. 

## Используя информацию, полученную при помощи команды history, выполнила модификацию и исполнение нескольких команд из буфера команд.

![](./image/снимок7.png)

## Используя информацию, полученную при помощи команды history, выполнила модификацию и исполнение нескольких команд из буфера команд.

![](./image/снимок7а.png)

## Используя информацию, полученную при помощи команды history, выполнила модификацию и исполнение нескольких команд из буфера команд.

![](./image/снимок7б.png)

## Выводы 

Приобрела практические навыки взаимодействия пользователя с системой посредством командной строки.


