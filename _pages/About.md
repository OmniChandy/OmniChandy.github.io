---
layout: archive
permalink: /About/
title: About
author_profile: true
comments: true
---

I don't like being average.
Born in China, decided to have a go in Australia.
I graduated from Monash with Master of Business Information Systems.
Determined to pursue a future in Data analysis direction.

{% include base_path %}


  <div class="grid__wrapper">
  {% for post in site.categories.About %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
  </div>
