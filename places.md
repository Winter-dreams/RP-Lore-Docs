---
layout: page
title: Places
permalink: /places/
---
<ul>
{% for place in site.places %}
  <h2>
    <a href="{{ place.url | relative_url }}">
      {{ place.title }}
    </a>
  </h2>
{% endfor %}
</ul>
