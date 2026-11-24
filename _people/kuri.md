---
layout: default
title:  "Kuri"
age: 14
---

# {{ page.title}}

{% if page.nicknames != empty and page.nicknames %}
Also known as {{ page.nicknames | join: ", " }}
{% endif %}

First-year at the academy.

<a href="essie.html">Essie's</a> Roommate.
