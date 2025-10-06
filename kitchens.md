---
title: "Kitchen Tools"
layout: archive
permalink: /kitchens/
author_profile: true
---
{% for kitchen in site.kitchens %}
  <h2><a href="{{ site.baseurl }}{{ kitchen.url }}">{{ kitchen.title }}</a></h2>
  <p><small>{{ kitchen.date | date: "%B %d, %Y" }}</small></p>
{% endfor %}
