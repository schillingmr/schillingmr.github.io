---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}
test test test

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
