---
layout: page
title: Organizations
permalink: /organizations/
---
<ul>
{% for organization in site.organizations %}
  <h2>
    <a href="{{ organization.url | relative_url }}">
      {{ organization.title }}
    </a>
  </h2>
{% endfor %}
</ul>
