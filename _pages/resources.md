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

{% capture resource_cards %}
{% for item in tools %}
  - image_path: {{ item.image_path | default: "/assets/images/default-thumbnail.jpg" }}
    alt: "{{ item.title }}"
    title: "{{ item.title }}"
    excerpt: "{{ item.excerpt }}"
    url: "{{ item.url }}"
    btn_label: "Download"
    btn_class: "btn--primary"
{% endfor %}
{% endcapture %}

{% assign resource_cards = resource_cards | markdownify %}

{% include feature_row id="resource_cards" %}
