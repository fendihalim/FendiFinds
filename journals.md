---
title: "Journals"
layout: archive
permalink: /journals/
---
{% for journal in site.journals %}
  <h2><a href="{{ site.baseurl }}{{ journal.url }}">{{ journal.title }}</a></h2>
  <p><small>{{ journal.date | date: "%B %d, %Y" }}</small></p>
{% endfor %}
