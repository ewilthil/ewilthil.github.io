---
layout: default
title:  "List of publications"
permalink: publications
---
## List of Publications
{% for pub in site.data.publications.papers %}
###### {{pub.title }}
*{{pub.authors}}*, {{pub.published-in}}.
{% endfor %}
