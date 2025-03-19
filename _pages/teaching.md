---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

- [Seasonal Schools](#seasonal-schools)
- [Teaching Assistant](#teaching-assistant)

## Seasonal Schools

{% for post in site.teaching reversed %}
  {% if post.role == 'Schools' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Teaching Assistant

{% for post in site.teaching reversed %}
  {% if post.role == 'TA' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
