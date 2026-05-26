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
  overlay_image: /assets/images/STEAMHead.svg #STEAMLogo.svg CassandraSTEAM_head.jpg /assets/images/coffee.jpg
  caption: "Cassandra STEAM Press"
  actions:
    - label: "Buy on Amazon"  
      url: "https://github.com/mmistakes/minimal-mistakes/"
    - label: "Buy on Ingram-Spark"
      url: "https://github.com"  
excerpt: "Getting Started with Entity Event-Driven Embedded Systems"
intro: 
  # - excerpt_class: "text-left" # Centered with `type="center"`
  # margin-left: 15%; width: 70%; 
  - excerpt: '<div style="text-align: left;">This series is a streamlined but gentle introduction to the world of Entity Event-Driven Embedded Systems.<br/><br/>
Using a cooperative multitasking approach, makers, hobbyists, students and professionals can learn how to build embedded systems that are capable of participating in Event-Driven Architectures.
<br/><br/> These step-by-step and straightforward guides take you from “Hello, world!” to implementing concurrency on your Pico W and Pico 2W systems. They simplify the complexity of implementing responsive and resource efficient embedded systems that can provide microservices and other data consumers / AI Agents with important important “real-time” event information about themselves and the physical world with which they interact.</div>'
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
  - image_path: /assets/images/Canva3D_vol3.png # Canva_Vol3_ComingSoon_600x809-2026.05.23.png # Vol3_600x840.jpg
    title: "Volume 3"
    excerpt: "**Expected Late Fall 2026: Communicating with the UART, I2C, and SPI Interfaces**<br/>An introduction to communicating with the UART, I2C, and SPI interfaces built into the Raspberry Pi Pico and Pico 2W"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row id="intro" type="center"%}    
{% include feature_row %} 
