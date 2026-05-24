---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# layout: home #splash
# author_profile: true
layout: splash # home
title: "Raspberry Pi Pico and Pico 2W"
# cta_label: "Learn More"
# cta_url: "/about/"
# <img src="/assets/images/STEAMLogo.svg" width="600" height="600">
header:
  overlay_color: "#000"
  # overlay_filter: "0.1"
  overlay_image: /assets/images/STEAMLogo.svg #/assets/images/CassandraSTEAM_head.jpg /assets/images/coffee.jpg
  caption: "Cassandra STEAM Press"
  actions:
    - label: "Buy on Amazon"  
      url: "https://github.com/mmistakes/minimal-mistakes/"
    - label: "Buy on Ingram-Spark"
      url: "https://github.com"  
excerpt: "Getting Started with Entity Event-Driven Embedded Systems"
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin.'  
# Centered with `type="center"`
feature_row:
  - image_path: /assets/images/Canva3D_vol1.png # Vol1_600x840.jpg
    title: "Volume 1"
    excerpt: "**GPIO and Asynchronous Programming with Microdot**<br/>A gentle introduction to the world of Entity Event-Driven Embedded Systems"
    url: "/about/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/Canva3D_vol2.png # Vol2_600x840.jpg
    title: "Volume 2"
    excerpt: "**Pulse Width Modulation and DC Motors**<br/>An introduction to the complex world of DC motors in Entity Event-Driven Embedded Systems"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary" # "btn--secondar"
  - image_path: /assets/images/Canva_Vol3_ComingSoon_600x809-2026.05.23.png # Canva3D_vol3.png Vol3_600x840.jpg
    title: "Volume 3"
    excerpt: "**Communicating with the UART, I2C, and SPI Interfaces**<br/>An introduction to communicating with the UART, I2C, and SPI interfaces built into the Raspberry Pi Pico and Pico 2W"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row id="intro" type="center" %}  
{% include feature_row %}
