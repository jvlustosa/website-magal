---
layout: page
title: Escritos
kicker: Capítulos
lead: A jornada de alto rendimento, escrita em primeira pessoa. Cada texto é um capítulo. O original completo vive no Substack.
permalink: /escritos/
description: Textos de Daniel Magalhães sobre concursos, ITA, IME, SEFAZ e mentalidade de alto rendimento.
---

<div class="cards">
{% for post in site.posts %}
<a class="card" href="{{ post.url | relative_url }}">
  {% if post.image %}<img src="{{ post.image | relative_url }}" alt="" width="800" height="450" loading="lazy">{% endif %}
  <div class="card-body">
    <h3>{{ post.title }}</h3>
    <p>{{ post.description }}</p>
  </div>
</a>
{% endfor %}
</div>

<p class="cta-row"><a class="btn btn-gold" href="https://danielmagal.substack.com/" rel="noopener">Assinar no Substack</a></p>
