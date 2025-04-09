---
layout: archive
title: "Demos"
permalink: /demos/
author_profile: true
---

{% include base_path %}
{% for demo in site.demos reversed limit: 10 %}
{% include archive-single.html demo=demo %}
{% endfor %}
