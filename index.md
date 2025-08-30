---
title: Butleriana CR
---

# Que es esta pagina????

Esta es una pagina dedicada a mis opiniones, basadas en noticias mensuales.

---

## Entradas recientes

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
