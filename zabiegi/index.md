---
layout: zabieg
title: Zabiegi
---
{% for page in site.pages %}
  {% if page.layout == 'zabieg' %}
  {% include zabieg_preview.html %}
  {% endif %}
{% endfor %}
