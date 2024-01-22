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

## Works in Progress
Seller Learning on an Auction Platform

Identification in Models with Agent Learning


## Working Papers
{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
{% endfor %}

## Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
