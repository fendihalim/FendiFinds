---
title: "Recipes"
layout: archive
permalink: /recipes/
author_profile: true
---

{% for recipe in site.recipes %}
  <h2><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.title }}</a></h2>
{% endfor %}
