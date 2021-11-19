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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

title: "Vastr-GAN: Versatile Apparel Synthesised from Text using a Robust Generative Adversarial Network"
collection: publications
# permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper was a part of my Machine Learning course project, done under the guidance of Professor Nipun Batra.'
# date: 2009-10-01
venue: 'CODS-COMAD 2022'
paperurl: 'http://Dhruvi-Lodhavia.github.io/files/paper1.pdf'
