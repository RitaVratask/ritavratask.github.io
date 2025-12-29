---
layout: default
title: Inicio
[Sobre mí](/about/) | [LinkedIn](https://www.linkedin.com/in/tu-usuario-de-linkedin).
---

### Cuando exploras la Tierra de Nadie

Aquí encontrarás mis artículos.

## 📑 Entradas recientes

<ul>
  {% for post in site.posts %}
    <li>
      <strong>{{ post.date | date: "%d/%m/%Y" }}</strong> — 
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% if site.posts.size == 0 %}
  *Aún no hay publicaciones, pero pronto habrá novedades.*
{% endif %}

---

## 🔗 Enlaces 
[Sobre mí]({{ site.baseurl }}/about/) | [LinkedIn](https://www.linkedin.com/in/tu-usuario-de-linkedin) | [GitHub](https://github.com/Ritavratask)
