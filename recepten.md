---
layout: page
title: Recepten
permalink: /recepten/
---



{% for recipe in site.recipes %}
  [{{ recipe.name }}]({{ recipe.url }})
{% endfor %}
