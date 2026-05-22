---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# layout: home #splash
# author_profile: true
layout: splash # home
title: "Raspberry Pi Pico and Pico 2W"
# <img src="/assets/images/STEAMLogo.svg" width="600" height="600">
header:
  overlay_color: "#000"
  # overlay_filter: "0.1"
  overlay_image: /assets/images/CassandraSTEAM_head.jpg #/assets/images/coffee.jpg
  caption: "Cassandra STEAM Press"
  actions:
    - label: "Buy on Amazon"
      url: "https://github.com/mmistakes/minimal-mistakes/"
    - label: "Buy on Ingram-Spark"
      url: "#bar"  
  # cta_label: "Learn More"
  # cta_url: "/about/"
excerpt: "Getting Started with Entity Event-Driven Embedded Systems"
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: /assets/images/feat1-1.jpg
    title: "Volume 1"
    excerpt: "GPIO and Asynchronous Programming with Microdot"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/feat1-2.jpg
    title: "Volume 2"
    excerpt: "Pulse Width Modulation and DC Motors"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary" # "btn--secondar"
  - image_path: /assets/images/feat1-3.jpg
    title: "Volume 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
      - image_path: /assets/images/feat1-3.jpg
    title: "Volume 4"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
      - image_path: /assets/images/feat1-4.jpg
---
{% include feature_row id="intro" type="center" %}  
{% include feature_row %}
