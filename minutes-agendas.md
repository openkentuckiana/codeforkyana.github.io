---
layout: page
title: Steering Committee Meeting Minutes and Agendas
use-site-title: true
---

<p>Here you will find agendas and minutes from Steering Committe meetings.</p>

{% for ma in site.minutes-agendas reversed %}
  <h2>
    <a href="{{ ma.url | prepend:site.baseurl }}">
      {{ ma.title }}
    </a>
  </h2>
{% endfor %}