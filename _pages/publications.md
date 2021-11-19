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
"Vastr-GAN: Versatile Apparel Synthesised from Text using a Robust Generative Adversarial Network", CODS-COMAD 2022 [Acceptance Rate = 21%]

-Dhruvi Lodhavia, Hetvi Shastri, Palak Purohit, Ronak Kaoshik and Nipun Batra