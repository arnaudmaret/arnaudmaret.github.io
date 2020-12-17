---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

- Ergodicity of the mapping class group action on super-maximal representations. (2020) Available here.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
