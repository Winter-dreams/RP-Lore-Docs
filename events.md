---
layout: page
title: Events
permalink: /Events/
---
<ul>
{% for event in site.events %}
  <h2>
    <a href="{{ event.url | relative_url }}">
      {{ event.title }}
    </a>
  </h2>
{% endfor %}
</ul>
