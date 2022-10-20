---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

title: "On the Learning Mechanisms in Physical Reasoning"
collection: publications
date: 2022-10-12
venue: 'NeuriPS 2022 conference'
website: 'https://lishiqianhugh.github.io/LfID_Page/'
citation: '*Li S, Wu K, Zhang C, et al. On the Learning Mechanisms in Physical Reasoning[J]. arXiv preprint arXiv:2210.02075, 2022.*'

[Download paper here](https://arxiv.org/pdf/2210.02075.pdf)
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
