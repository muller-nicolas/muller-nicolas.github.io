---
layout: archive
title: "News"
permalink: /news/
author_profile: true
keywords: "turbulence, fluid dynamics, fluids, superfluids, quantum fluids, numerical simulations, magnetohydrodynamics, dynamo, geodynamo, reversals, solar wind, magnetoacoustic waves, wave turbulence"
---

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

