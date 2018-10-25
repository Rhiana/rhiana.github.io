---
layout: page
title: Portfolio
subtitle: Personal and Professional Websites, Hack Day Projects
permalink: /portfolio/
---

<div class="portfolio-page wrapper">

  {% for post in site.posts %}
    {% if post.layout == "portfolio" %}
      {{ post }}
    {% endif %}
  {% endfor %}

</div>
