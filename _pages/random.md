---
layout: archive
title: "Random"
permalink: /random/
author_profile: true
---

{% include base_path %}

{% for post in site.random reversed %}
  {% include archive-single.html %}
{% endfor %}
