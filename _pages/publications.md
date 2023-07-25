---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

- [Journal Papers](#journal-papers)
- [Conference Papers](#conference-papers)

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Journal Papers

{% for post in site.publications reversed %}
  {% if post.type == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Conference Papers

{% for post in site.publications reversed %}
  {% if post.type == 'proceedings' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
