---
title: Project Ideas
layout: post
author: Jordan
---

## Languages

{% capture swift %}
- Webcam App
  - video (and audio?) forwarding
  - wired?
  - usb tcp server
  - local wireless tcp server
{% endcapture %}
{% include details.md label="Swift" content=swift %}

{% capture java %}
- Webcam Client
  - On Computer
  - Connects to tcp server (wired or wireless)
  - Pretends to be a webcam and forwards video (and audio?)
{% endcapture %}
{% include details.md label="Java" content=java %}

{% capture py %}
- Refactor API
    - More logical code layout
    - Remove unused media code (make backup)
    - Add more functionality using Google APIs
{% endcapture %}
{% include details.md label="Python3" content=py %}
