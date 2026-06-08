---
# https://www.amazon.com/dp/B0G3M799HQ
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
    - label: "Buy on Amazon.com"  
      url: "https://www.amazon.com/Getting-Started-Event-Driven-Embedded-Systems/dp/B0G2WKWC43"
#    - label: "Buy on IngramSpark.com"
#      url: "https://www.IngramSpark.com"  
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
    url: /vol1_landing/
    btn_label: "Read More"
    btn_class: "btn--success"
  - image_path: /assets/images/Canva3D_vol2.png # Vol2_600x840.jpg
    title: "Volume 2"
    excerpt: "**Pulse Width Modulation and DC Motors**<br/>An introduction to the complex world of DC motors in Entity Event-Driven Embedded Systems"
    url: /vol2_landing/
    btn_label: "Read More"
    btn_class: "btn--success" # "btn--secondar"
  - image_path: /assets/images/Canva3D_vol3.png # Canva_Vol3_ComingSoon_600x809-2026.05.23.png # Vol3_600x840.jpg
    title: "Volume 3"
    excerpt: "**Expected Late Fall 2026: Communicating with the UART, I2C, and SPI Interfaces**<br/>An introduction to communicating with the UART, I2C, and SPI interfaces in Entity Event-Driven Embedded Systems"
    url: /vol3_landing/ #"#test-link"
    btn_label: "Read More"
    btn_class: "btn--success"
  
---
{% include feature_row id="intro" type="center"%}    
{% include feature_row %} 

**Who These Books Are For**   <br/>
The primary audience for these books are makers, hobbyists, students and professionals who want to learn more about Entity Event-Driven Embedded Systems using MicroPython's asyncio library and Microdot. 
It is assumed you know the basics of Python and have a host computer (a Raspberry Pi, Windows PC, or Apple mac), a Pico W or Pico 2W (these are available with the headers already soldered on), and some electronic components (such as a breadboard, LEDs, a button switch and Piezo buzzer). 

**What Readers are Saying**  <br/>
     
<i class="fas fa-star" style="color: #f39c12;"></i>
<i class="fas fa-star" style="color: #f39c12;"></i>
<i class="fas fa-star" style="color: #f39c12;"></i>
<i class="fas fa-star" style="color: #f39c12;"></i>
<i class="fas fa-star" style="color: #f39c12;"></i> 5 stars 

*A new way for computer science education to compliment AI.*  
  
Byron Mattingly's new books help us reconceptualize computer science education in a way that complements the revolution in the computational worldview induced by developments in agent-centered AI and machine learning.  

The Raspberry Pi Pico W and 2W can help us redesign high school and junior college computer science classes to focus on computation in the design of experiments aimed at discovering new data that cannot be produced simply by further scraping the already well-scraped internet.  

The second volume–which can be read independently or in sequence with the first–should be invaluable for its discussion of DC motors. These two volumes give future students the skills they need to develop new applications of embedded systems in the design of computation-based devices in Chemistry, Physics, and Biology, leading to new scientific and commercial products.  

As a bonus, Mattingly's books show how to write elegant, well-documented Python code.  

---  
**About the Author**   <br/>
Byron Mattingly has been an embedded systems software engineer and hands-on technical manager for over 20 years in regulated development in the medical devices, pharmaceutical, and avionics industries. Currently his work is focused on designing and integrating complex IT systems and training and deploying AI/ML models interacting with embedded systems. An early adopter of the Raspberry Pi platform, he is an open source contributor and avid proponent of STEAM education.
