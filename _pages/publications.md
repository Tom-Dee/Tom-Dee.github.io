---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


Bonilla, S., Dee, T. S., & Penner, E. K. (2021). Ethnic studies increases longer-run academic engagement and attainment. Proceedings of the National Academy of Sciences, 118(37).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{BDqIRPkAAAAJ.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
