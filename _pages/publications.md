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
Learning in Auction Platforms with Endogenous Bidder Entry

Hospital Productivity and Learning with COVID-19


## Working Papers
{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
{% endfor %}

## Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
