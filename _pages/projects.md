---
layout: archive
permalink: projects/
title: "projects"
excerpt: "My current projects."
header:
  overlay_image: /assets/images/default.jpg
  
last_modified_at: 2018-01-10T11:22:24-05:00
---

<div>
{% for post in site.categories.projects %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

