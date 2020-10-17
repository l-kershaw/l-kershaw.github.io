---
layout: archive
title: "Software"
permalink: /software/
sitemap: false
author_profile: true
entries_layout: grid
redirect_from:
  - /programs
  - /coding
---



{% include base_path %}

{% for post in site.software reversed %}
  {% include archive-single.html %}
{% endfor %}
