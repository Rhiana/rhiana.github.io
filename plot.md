---
layout: page
title: Plot
subtitle: Events, conferences, camps, certificates and awards
permalink: /about/
---
<div class="about-page wrapper">

{% for post in site.posts %}
  {% if post.layout == "plot" %}
    {{ post }}
  {% endif %}
{% endfor %}

</div>
