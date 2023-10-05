---
permalink: /
title: "This is the frontpage of our website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% include base_path %}

## New updates 

{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}
