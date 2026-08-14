---
title: "Resources"
permalink: /resources/
layout: single
author_profile: true
---

## Resources & Tools  
Free tools, templates, calculators, and practical resources for coaches, athletes, and applied sport scientists.

---

{% assign tools = site.resources | sort: "title" %}

<div class="feature__wrapper">
  {% for item in tools %}
    <div class="feature__item">
      <div class="archive__item">
        {% if item.image_path %}
          <div class="archive__item-teaser">
            <img src="{{ item.image_path | relative_url }}" alt="{{ item.title }}">
          </div>
        {% endif %}
        <div class="archive__item-body">
          <h2 class="archive__item-title">{{ item.title }}</h2>
          {% if item.excerpt %}
            <div class="archive__item-excerpt">{{ item.excerpt | markdownify }}</div>
          {% endif %}
          {% if item.download %}
            <p><a href="{{ item.download | relative_url }}" class="btn btn--primary">Download</a></p>
          {% endif %}
        </div>
      </div>
    </div>
  {% endfor %}
</div>
