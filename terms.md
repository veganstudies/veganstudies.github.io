---
layout: page
title: "용어 정리"
---
<ul>
{% assign terms = (site.terms | sort: 'title') %}
{% for term in terms %}
  <li><a href="{{ term.url }}">{{ term.title }}</a></li>
{% endfor %}
</ul>
