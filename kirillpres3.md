---
## Front matter
lang: ru-RU
title: Лабораторная работа №3
author: |
	Сидоракин
institute: |
	 RUDN University, Moscow, Russian Federation
date: Сентябрь, 2021 Москва

## Formatting
toc: false
slide_level: 2
theme: metropolis
sansfont: NotoMono-Regular
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---
## Цель лабораторной работы

Получение практических навыков работы в консоли с атрибутами файлов для групп пользователей

# Процесс выполнения лабораторной работы

## Создаю учетную запись пользователя guest

![Создание guest](image/1.jpg){ #fig:001 width=50% }

## Задаю пароль для пользователя guest

![Пароль](image/2.jpg){ #fig:002 width=50% }

## Создаем второго пользователя

![Пользователь guest2](image/3.jpg){ #fig:003 width=50% }

## Добавляем пользователя guest2 в группу guest

![Директория](image/4.jpg){ #fig:004 width=70% }

## Осуществляем вход в систему от двух пользователей

![Guest1](image/5.jpg){ #fig:005 width=70% }

## Второй пользователь

![Guest2](image/5.1.jpg){ #fig:006 width=70% }

## Определяем директории пользователей

![pwd1](image/6.jpg){ #fig:007 width=70% }

## Определяем директории пользователей

![pwd2](image/6.1.jpg){ #fig:008 width=70% }



## Сравнение информации /etc/group

![group](image/7.jpg){ #fig:009 width=50% }

![group](image/7.1.jpg){ #fig:010 width=50% }

![id guest](image/7.2.jpg){ #fig:009 width=50% }

![id guest2](image/7.3.jpg){ #fig:009 width=50% }

## Просматриваем файл "/etc/passwd/".

![Сравниваем информацию](image/8.jpg){ #fig:010 width=50% }

## Просматриваем файл "/etc/passwd/".

![Сравниваем информацию](image/8.1.jpg){ #fig:009 width=50% }

## Регистрируем guest2

![Регистрация](image/9.jpg){ #fig:011 width=50% }

## Изменяем права директории

![Права директории](image/10.jpg){ #fig:012 width=50% }

## Снимаем атрибуты с директории

![Атрибуты](image/11.jpg){ #fig:013 width=50% }

## Минимально необходимые права для выполнения операций

![Права](image/min.jpg){ #fig:017 width=50% }


## Вывод
Мы приобрели практические навыки работы в консоли с атрибутами файлов, закрепели теоретические основы дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux.