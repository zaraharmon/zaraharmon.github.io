---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}
% add reversed after site.publications to get the publications to show up in reverse order. 
