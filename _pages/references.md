---
layout: archive
title: "References"
permalink: /references/
author_profile: false
---

{% include base_path %}

{% for post in site.references reversed %}
  {% include archive-single.html %}
{% endfor %}
