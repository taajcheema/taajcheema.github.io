---
layout: media
title: Projects
share: false
permalink: /projects/
image:
  feature: mcway_falls.jpg
---

<div class="tiles">                                                             
{% for post in site.categories.projects %}
  {% include post-grid.html %}                                                  
{% endfor %}                                                                    
</div>

<!--
<p>
<a href="https://github.com/jasonpchang/pitchfx_sql">Create your own PitchFX SQL database using Python </a>
</p>
-->
