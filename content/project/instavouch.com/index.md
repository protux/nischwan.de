---
title: instavouch.com 
summary: A webshop for buying vouchers with alternative payment providers.
tags:
- Python
- Django
- Full Stack 
date: "2019-07-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Landing Page of instavouch.com 
  focal_point: Smart

links:
- icon: link
  icon_pack: fas
  name: Visit the projects website
  url: https://instavouch.com/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

In 2017 friends and me figured, there is no proper platform for buying vouchers for people without access to credit cards or similar which is customer focused. All competitors had either no good vouchers to offer or where very customer unfriendly. We sat together and agreed on changing it.

A few month later, the first version went live. Meanwhile the platform attracted many customers and grew. 

Today, the platform is based on Python/ Django, with Celery workers for the heavy lifting and redis as worker queue. The platform is distributed across multiple datacenters for a maximum failure safe user experience.

A CI/CD setup makes sure, that we are always able to deliver new features for our users.
