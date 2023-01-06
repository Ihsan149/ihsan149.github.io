---
layout: archive
title: "Patents"
permalink: /patents/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=eod9uX0AAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.patents reversed %}
  {% include archive-single.html %}
{% endfor %}

