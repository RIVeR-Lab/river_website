---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "NRMM"
summary: "Physics-based autonomous terrain traversability for multi-terrain vehicles."
authors: []
tags: []
categories: []
date: 2022-06-25T20:10:49-04:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Overview

The Nato-Reference Mobility Model (NRMM) is a physics-based vehicle-terrain prediction system. It is mostly a text-based code system developed in Fortran, which was originally designed in the mainframe era. This code suite was most recently updated in 2021, allowing for it to more accurately perform the function it was designed for, the standardization of vehicle performance in terms of mobility. Through a collection of equations and algorithms the system is meant to simulate cross-country movement of vehicles. The system models a vehicle's interaction with various terrains and various components of those terrains. It cares about interactions with soil strength, tree stems of various sizes and spacing, approach angles into ditches and streams, and etc. The system is most interested in determining the maximum potential speed of a given vehicle through a specified region. The purpose of this project is to take this currently developed system and design additional submodules for the purpose of accommodating more advanced levels of technology and automation.

![s](nrmm1.png)
![s](nrmm2.png)
