---
layout: default
Title: "Home"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="About Me" %}
{% endif %}  
