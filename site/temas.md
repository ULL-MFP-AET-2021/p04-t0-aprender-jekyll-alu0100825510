---
layout: page
title: Temas
permalink: /temas/
---

Temario

<div class="posts">
  {% for tema in site.temas %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ tema.url }}">{{ tema.title }}</a></h1>

      <div class="entry">
        {{ tema.excerpt }}
      </div>
    </article>
  {% endfor %}
</div>