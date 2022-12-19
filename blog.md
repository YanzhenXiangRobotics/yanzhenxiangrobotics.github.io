---
layout: default
title: "Blog"
---
Test Test Test

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
