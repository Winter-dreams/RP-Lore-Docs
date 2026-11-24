---
layout: default
title:  "Name"
nicknames:
    - Nickname 1
    - Nickname 2
---

# {{ page.title}}

{% if page.nicknames != empty and page.nicknames %}
Also known as {{ page.nicknames | join: ", " }}
{% endif %}

<a href="sample_person.html">Sample Person's</a> Roommate.
