---
title: Butleriana CR
---

# Butleriana CR

Butleriana CR es una pagina dedicada a blogposts mensuales. Cada blogpost contiene una noticia relevante relacionada a la disciplina de la Computación, y su papel en la sociedad costarricense.

---

## Entradas recientes

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>

