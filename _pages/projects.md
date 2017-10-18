---
layout: media
title: Projects
share: false
permalink: /projects/
---

<div class="tiles">                                                             
{% for post in site.categories.projects %}
  {% include post-list.html %}                                                  
{% endfor %}                                                                    
</div><!-- /.tiles -->
