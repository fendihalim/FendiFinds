---
title: "Recipes"
layout: archive
collection: recipes
permalink: /recipes/
author_profile: true
---

{% for recipe in site.recipes %}
  <h2><a href="{{ recipe.url }}">{{ recipe.title }}</a></h2>
{% endfor %}
