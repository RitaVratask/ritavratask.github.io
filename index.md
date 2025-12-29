---
layout: default
title: Inicio
[Sobre mí](/about/) | [LinkedIn](https://www.linkedin.com/in/tu-usuario-de-linkedin).
---

### Cuando exploras la Tierra de Nadie

Aquí encontrarás mis artículos.

#### Entradas recientes:
{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }}) - {{ post.date | date_to_string }}
{% endfor %}
