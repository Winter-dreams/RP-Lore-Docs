---
layout: page
title: People
permalink: /people/
---
<ul>
{% for person in site.people %}
  <h2>
    <a href="{{ person.url | relative_url }}">
      {{ person.title }} ({{ person.age}})
    </a>
  </h2>
{% endfor %}
</ul>
