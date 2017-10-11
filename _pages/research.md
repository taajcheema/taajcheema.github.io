---
layout: media
title: Research
share: false
permalink: /research/
---

<div class="grid__wrapper">
  {% for post in site.categories.research %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
