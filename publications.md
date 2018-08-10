---
layout: page
title: Publications
subtitle: Online Articles and Blog posts
permalink: /publications/
---

<div class="publications-page wrapper">

  {% for post in site.posts %}
    {% if post.layout == "publication" %}
      {{ post }}
    {% endif %}
  {% endfor %}

</div>
