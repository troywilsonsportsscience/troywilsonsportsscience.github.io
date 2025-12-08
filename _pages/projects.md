---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
---

## Projects  
These are projects I've completed in applied sport science, strength and conditioning, data analytics, and performance systems.

---

## Case Studies  
Cases studies  will be added as I formalize them.

{% assign cs = site.case-studies | sort: "title" %}
{% include feature_row id="case_studies" %}

{% capture case_studies %}
{% for item in cs %}
  - image_path: {{ item.image_path | default: "/assets/images/default-thumbnail.jpg" }}
    alt: "{{ item.title }}"
    title: "{{ item.title }}"
    excerpt: "{{ item.excerpt | default: item.description }}"
    url: "{{ item.url }}"
    btn_label: "View"
    btn_class: "btn--primary"
{% endfor %}
{% endcapture %}
{% assign case_studies = case_studies | markdownify %}
