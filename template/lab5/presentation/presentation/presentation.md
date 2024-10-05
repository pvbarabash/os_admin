---
## Front matter
lang: ru-RU
title: Презентация по выполнению лабораторной работы 
subtitle: Лабораторная работа №5
author:
  - Барабаш П.В.
institute:
  - Российский университет дружбы народов, Москва, Россия
  
date: 5 октября 2024

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
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Барабаш Полина Витальевна
  * студентка 2 курса, НПИбд-01-23
  * Российский университет дружбы народов
  * [1132231841@pfur.ru](mailto:1132231841@pfur.ru)

:::
::: {.column width="30%"}

![](./image/я.png)

:::
::::::::::::::

## Цели и задачи

- Получить навыки управления системными службами операционной системы посредством systemd.


# Службы

##  Команды по работе со службами

systemctl start — запуск службы

systemctl status — проверка статуса службы

systemctl enable — добавление службы в автозапуск

systemctl disable — удаление службы из автозапуска

##  Проверка зависимостей службы

systemctl list-dependencies  — вывести список зависимостей юнита 

systemctl list-dependencies ... --reverse — вывести список юнитов, которые зависят от данного юнита


##  Конфликты юнитов

systemctl stop — выгрузить службу

systemctl mask — заблокировать службу


## Изолируемые цели

systemctl isolate rescue.target — переключить операционную систему в режим восстановления

systemctl get-default — вывести цель по умолчанию 

systemctl set-default — установить цель по умолчанию 


# Выводы

Я получила навыки управления системными службами операционной системы посредством systemd.
