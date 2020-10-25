---
layout: archive
title: "Coding"
permalink: /coding/
sitemap: false
author_profile: true
redirect_from:
  - /programs
  - /software
---



{% include base_path %}

{% for post in site.coding reversed %}
  {% include archive-single-project.html %}
{% endfor %}
