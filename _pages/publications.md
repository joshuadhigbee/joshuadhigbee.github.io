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
<b>Learning and Information Design on an Auction Platform</b> (Job Market Paper)

<b>Identification in Models with Agent Learning</b>

<b>Bargaining, Bartering, and Price Rigidity in Corporate Contracting</b> (with Matthew Jennejohn, Cree Jones, and Eric Talley)


## Working Papers
{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
{% endfor %}

## Publications
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
