---
layout: page
title: About
subtitle: Events, conferences, camps, certificates and awards
permalink: /about/
---
<div class="about-page wrapper">

{% for post in site.posts %}
  {% if post.layout == "about" %}
    {{ post }}
  {% endif %}
{% endfor %}

</div>
