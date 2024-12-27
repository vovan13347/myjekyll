---
layout: post
title: "Мой первый пост"
date: 2024-12-25
categories: [first-post]
---

{% if page.title %}
    {{page.title }}
{% endif %}


Привет, мир! Это мой первый пост на этом сайте. Я надеюсь, что он будет полезным и интересным для вас. Если у вас есть вопросы или предложения, не стесняйтесь обращаться. Давайте начнем знакомиться! 😊


# Пример с for:
{% for i in (1..10) %}
    {{i}}
{% endfor %}

# Пример с while:
{% assign max = 100000 %}

{% for i in (1..max) %}
    {% if i <= 5 %}
        {{i}}
    {% else %}
       {% break %}
    {% endif %}
{% endfor %}


# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

{% if page.title contains 'первый' %}
    Содержит
{% endif %}


{{ "первый " | append: "пост" }}
<br>
{{ "первый " | prepend: "пост" }}

![Картика](https://img1.goodfon.ru/wallpaper/nbig/9/87/priroda-gory-leto-svet-solnca.jpg)
