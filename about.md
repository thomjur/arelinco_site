---
layout: default
title: About ARELINCO
---

# Hi

This is about us!

{% for item in site.data.members %}
- {{ item.name }} ({{ item.position }})
{% endfor %}