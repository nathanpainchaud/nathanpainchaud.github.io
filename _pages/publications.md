---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

- [Journal Papers](#journal-papers)
- [Conference Papers](#conference-papers)

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
