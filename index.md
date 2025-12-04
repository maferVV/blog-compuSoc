---
title: Butleriana CR
---

# Butleriana CR

Butleriana CR fue un proyecto dedicado a blogposts mensuales (de Agosto a Noviembre 2025). Cada blogpost contiene una noticia relevante relacionada a la disciplina de la Computación, y su papel en la sociedad costarricense.

Agosto inicia con un comentario sobre el sabotaje como herramienta de cambio en una era marcada por el fascismo y la vigilancia.

Setiembre comenta sobre Palantir. Una empresa sustentada, en parte, por profesionales de la industria de la computación.

Octubre se ubica en la Universidad de Costa Rica. La noticia habla sobre la violencia a las instituciones nacionales, y su relevancia en nuestras vidas.

Noviembre intenta enlazar todos los temas vistos en los blogposts anteriores, con Palestina en el medio.

Información para el proyecto
Nombre de la persona estudiante | María Fernanda Vega |
Carne Universitario | B78244 |
Curso | Computación y Sociedad |
Grupo | 003 |
Fecha de Entrega | lunes, 1 de diciembre de 2025 |
Nombre del Profesor | Prof. Alexander Barquero Elizondo |


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

