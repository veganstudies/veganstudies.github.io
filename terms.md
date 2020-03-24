---
layout: page
title: "용어 정리"
permalink: /terms/
---
비거니즘/동물권 관련 용어들을 되도록 짧고 쉽게 설명하고, 관련 내용을 더 자세히 알 수 있는 문서들을 정리했습니다.

<ul>
{% assign terms = site.terms | sort: 'title' %}
{% for term in terms %}
  <li><a href="{{ term.url }}">{{ term.title }}</a></li>
{% endfor %}
</ul>
