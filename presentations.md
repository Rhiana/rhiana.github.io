---
layout: page
title: Presentations
subtitle: Talks given at Conferences, Meetups and companies
permalink: /presentations/
---

<div class="presentation-page wrapper">

  {% for post in site.posts %}
    {% if post.layout == "presentation" %}
      {{ post }}
    {% endif %}
  {% endfor %}

 </div>
