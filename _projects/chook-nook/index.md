---
layout: post
title: Chook Nook
description: After building the run and coop for my small flock, a year before it was cool, I knew there was data to be had. To monitor and care for my flock, I've created a sytem using a Rasperry Pi and several other hardware pieces. I had several solar panels from when I moved up from California and this was a great use case for offsetting my power consumption. The project started out using a simple temperature sensor and relay, now includes several more sensors and an Edge TPU for image classifcation. 

skills: 
  - Soldering
  - Arduino / Raspberry Pi 
  - Python
  - Networking
  - BIND\DNS
  - Machine Learning
  - HTML
  - Photovoltaics
  - InfluxDB

main-image: /hello_ladies.jpg
---

---
## The Challanges
Taking care of chickens while working full-time means many hours hoping the crow I hear during my Zoom meeting isn&#39;t anything important and just an egg announcement. Chickens, while hardy, can still suffer from frostbite on their toes, combs and waddles. I wanted to make sure the coop wasn&#39;t getting too cold at night while minimizing the fire hazard and automating wherever possible. 

All of this additional hardware means a larger energy footprint and enviormental impact. Being able to mitigate any power consumption is always a major factor in determining any solutions for any personal project. Not just for the immediate finical impact, but for long term sustainability.

I didn&#39;t want my consumer grade cameras to be exposed to the internet while still being able to operate as they are intended to. Keeping a low price point for electronics that are going to be outside and in dirty enviorments and still have a small form factor wasn&#39;t a challange persay, but the most popular had mutiple security incidents with little no respsability for their lack of a proper secuirty posture and configuration mangement. 

## The Solutions
The first step was finding the proper 
### The Hardware
- Raspberry PI 
- DHT22 sensors (deprecated)
- SHT32 sensor (upgrade)
- 2 Channel relay
- WYZE Cameras (being replaced)
- TAPO Cameras (replacement)


### The Software
- Raspbian Buster
- InfluxDB
- NGINX
- Python
  - FastAPI
  - Flask


## Building the Coop
{% include image-gallery.html images="building_the_coop.jpg" height="400" %}
{% include image-gallery.html images="building_the_coop2.jpg" height="400" %} 
{% include image-gallery.html images="building_the_coop3.jpg" height="400" %} 
{% include image-gallery.html images="building_the_coop4.jpg" height="400" %} 
{% include image-gallery.html images="building_the_coop5.jpg" height="400" %} 
{% include image-gallery.html images="building_the_coop6.jpg" height="400" %} 
{% include image-gallery.html images="building_the_coop7.jpg" height="400" %} 