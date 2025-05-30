---
## Front matter
lang: ru-RU
title: Лабораторная работа №14
subtitle: Статическая маршрутизация в Интернете. Настройка
author:
  - Шуваев С. А.
institute:
  - Российский университет дружбы народов, Москва, Россия

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
::: {.column width="50%"}

  * Шуваев Сергей Александрович
  * студент
  * Российский университет дружбы народов
  * [1032224269@pfur.ru](mailto:1032224269@pfur.ru)
  * <https://Grinders060050.github.io/ru/>

:::
::: {.column width="25%"}

![](./image/0.jpg)

:::
::::::::::::::

## Цель работы

Настроить взаимодействие через сеть провайдера посредством статической маршрутизации локальной сети организации с сетью основного здания, расположенного в 42-м квартале в Москве, и сетью филиала, расположенного в г. Сочи.

## Задание

1. Настроить связь между территориями.
2. Настроить оборудование, расположенное в квартале 42 в Москве.
3. Настроить оборудование, расположенное в филиале в г. Сочи.
4. Настроить статическую маршрутизацию между территориями.
5. Настроить статическую маршрутизацию на территории квартала 42 в г.
Москве.
6. Настроить NAT на маршрутизаторе msk-donskaya-gw-1.
7. При выполнении работы необходимо учитывать соглашение об именовании.

# Выполнение лабораторной работы

## Настройка линка между площадками

![Настройка интерфейсов коммутатора provider-shuvayev-sw-1](image/1.png){#fig:001 width=40%}

## Настройка линка между площадками

![Настройка интерфейсов маршрутизатора msk-donskaya-shuvayev-gw-1](image/2.png){#fig:003 width=50%}

## Настройка линка между площадками

![Настройка интерфейсов маршрутизатора msk-q42-shuvayev-gw-1](image/3.png){#fig:002 width=50%}

## Настройка линка между площадками

![Настройка интерфейсов коммутатора sch-sochi-shuvayev-sw-1](image/4.png){#fig:004 width=50%}

## Настройка линка между площадками

![Настройка интерфейсов маршрутизатора sch-sochi-shuvayev-gw-1](image/5.png){#fig:005 width=50%}

## Настройка площадки 42-го квартала

![Настройка интерфейсов маршрутизатора msk-q42-shuvayev-gw-1](image/6.png){#fig:006 width=40%}

## Настройка площадки 42-го квартала

![Настройка интерфейсов коммутатора msk-q42-shuvayev-sw-1](image/7.png){#fig:007 width=50%}

## Настройка площадки 42-го квартала

![Настройка интерфейсов маршрутизирующего коммутатора msk-hostel-shuvayev-gw-1](image/8.png){#fig:008 width=40%}

## Настройка площадки 42-го квартала

![Настройка интерфейсов коммутатора msk-hostel-shuvayev-sw-1](image/9.png){#fig:009 width=50%}

## Настройка площадки в Сочи

![Настройка интерфейсов маршрутизатора sch-sochi-shuvayev-gw-1](image/10.png){#fig:010 width=50%}

## Настройка площадки в Сочи

![Настройка интерфейсов коммутатора sch-sochi-sw-1](image/11.png){#fig:011 width=50%}

## Настройка маршрутизации между площадками

![Настройка маршрутизатора msk-donskaya-gw-1](image/12.png){#fig:012 width=50%}

## Настройка маршрутизации между площадками

![Настройка маршрутизатора msk-q42-gw-1](image/13.png){#fig:013 width=50%}

## Настройка маршрутизации между площадками

![Настройка маршрутизатора sch-sochi-gw-1](image/14.png){#fig:014 width=50%}

## Настройка маршрутизации на 42 квартале

![Настройка маршрутизатора msk-q42-gw-1](image/15.png){#fig:015 width=50%}

## Настройка маршрутизации на 42 квартале

![Настройка интерфейсов маршрутизирующего коммутатора msk-hostel-gw-1](image/16.png){#fig:016 width=50%}

## Настройка NAT на маршрутизаторе msk-donskaya-gw-1

![Настройка NAT на маршрутизаторе msk-donskaya-gw-1](image/17.png){#fig:017 width=40%}

## Проверка настроек

![Проверка доступа администратора с Донской к маршуртизируюшим устройствам](image/18.png){#fig:018 width=40%}

## Проверка настроек

![Проверка доступа в Интернет](image/19.png){#fig:019 width=50%}

## Выводы

В результате выполнения лабораторной были приобретены практические навыки по настройке взаимодействие через сеть провайдера посредством статической маршрутизации локальной сети организации с сетью основного здания, расположенного в 42-м квартале в Москве, и сетью филиала, расположенного в г. Сочи.