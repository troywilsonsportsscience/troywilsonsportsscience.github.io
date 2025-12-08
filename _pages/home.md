---
layout: splash
title: "Troy Wilson l Sport Science"
permalink: /

header:
  overlay_color: "#0b1120"
  overlay_filter: "0.65"
  overlay_image: "/assets/images/hero-banner2.png"
  actions:
    - label: "View Services"
      url: "/services/"
    - label: "View Projects"
      url: "/projects/"

intro:
  - excerpt: "Bridging applied sports science, strength and conditioning, and data analytics to help athletes, coaches, and organizations make better decisions."

feature_row:
  - image_path: /assets/images/performance-services.png
    alt: "Performance testing and monitoring"
    title: "Performance Services"
    excerpt: "Testing, monitoring, and strength & conditioning support for individuals and teams."
    url: "/services/"
    btn_label: "View services"
    btn_class: "btn--primary"

  - image_path: /assets/images/sport-science-projects.png
    alt: "Dashboards and analytics"
    title: "Sports Science Projects"
    excerpt: "Dashboards, KPIs, and analytical tools built from real high-performance environments."
    url: "/projects/"
    btn_label: "See projects"
    btn_class: "btn--primary"

  - image_path: /assets/images/data-tools.png
    alt: "Data tools and resources"
    title: "Resources & Tools"
    excerpt: "Templates, calculators, and resources for coaches and practitioners."
    url: "/resources/"
    btn_label: "View resources"
    btn_class: "btn--primary"
---

{% include intro %}

{% include feature_row id="feature_row" %}
