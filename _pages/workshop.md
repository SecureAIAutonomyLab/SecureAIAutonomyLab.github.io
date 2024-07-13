---
# layout: archive
title: "Workshop Page Hello World"
permalink: /workshop/
author_profile: true
# <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
---
### Hello World ###
{% if site.author.googlescholar %}
   
{% endif %}

{% include base_path %}

{% for post in site.workshop reversed %}
  {% include archive-single.html %}
{% endfor %}
