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

Unpublished notes:
======
* A note on Taylor expansion of real function, available on [https://arxiv.org/abs/2004.00474](https://arxiv.org/abs/2004.00474)


