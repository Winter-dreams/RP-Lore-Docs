---
layout: page
title: Concepts
permalink: /concepts/
---
<ul>
{% for concept in site.concepts %}
  <h2>
    <a href="{{ concept.url | relative_url }}">
      {{ concept.title }}
    </a>
  </h2>
{% endfor %}
</ul>
