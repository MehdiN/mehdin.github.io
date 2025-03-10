---
layout: archive
title: "Research Projects"
permalink: /research/
author_profile: true
redirect_from:
  - /project
  - /projects
---

This is the place where I document my past and ongoing research projects.

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
