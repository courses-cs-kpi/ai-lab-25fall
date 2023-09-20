---
layout: page
title: Про предмет
description: Загальна інформація.
nav_order: 1
---

# Про предмет
{:.no_toc}

## Зміст
{: .no_toc .text-delta }

1. TOC
{:toc}

---

{% assign overview = site.slides | where: "title", "Огляд" | first %}
{{ overview.content }}


Потрiбнi навички
: - Рівень володіння англійською мовою не нижче А2.
- **Математика**: знання та вміння використовувати обчислення, аналітичну геометрію, лінійну алгебру та теорію ймовірностей.
- **Програмування**: вміння програмувати на Python.


Підручники
: 1. Goodfellow, I., Bengio, Y., & Courville, A. (2016).  [*Deep Learning.* ](https://www.deeplearningbook.org/) MIT press.
2. Russell, S., & Norvig, P. (2021). [*Artificial Intelligence: A Modern Approach.*](https://www.amazon.com/Artificial-Intelligence-A-Modern-Approach/dp/0134610997#customerReviews)


## На випадок повітряної тривоги
{% assign specifics = site.slides | where: "title", "Повітряна тривога" | first %}
{{ specifics.content }}

## Особливостi
{% assign specifics = site.slides | where: "title", "Особливостi" | first %}
{{ specifics.content }}

## Система оцiнювання
{% assign grading = site.slides | where: "title", "Система оцiнювання" | first %}
{{ grading.content }}


## Кодекс честi
{% assign honorcode = site.slides | where: "title", "Кодекс честi" | first %}
{{ honorcode.content }}


## Як успішно завершити курс?
{% assign succeed = site.slides | where: "title", "Як успішно завершити курс?" | first %}
{{ succeed.content }}