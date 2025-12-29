---
layout: default
title: Inicio
---

### Cuando exploras la Tierra de Nadie

En este blog publico artículos sobre cómo analizo amenazas y desarrollo detecciones basadas en análisis estático y dinámico. Mi objetivo es sencillo: compartir investigaciones técnicas que muestren como puedo ayudar a fortalecer la defensa estratégica de cualquier organización.

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
[Sobre mí]({{ site.baseurl }}/about/) | [LinkedIn](https://www.linkedin.com/in/silvia-hernández-sánchez-899022121/) | [GitHub](https://github.com/Ritavratask)
