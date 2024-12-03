---
layout: page
title: Recepten
permalink: /recepten/
---



{% for recipe in site.recipes %}
  [{{ recipe.title }}]({{ recipe.url }})
{% endfor %}
