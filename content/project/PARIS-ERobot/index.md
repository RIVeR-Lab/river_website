---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "PARIS E-Robot"
summary: "For air-sealing in attic crawlspaces, a robot should be able to access most of typical narrow locations in the attic crawlspace, carry the tools required for air-sealing (spray gun, sealant can), and precisely apply spray foam sealant to the locations to be sealed."
authors: []
tags: []
categories: []
date: 2022-06-25T19:40:57-04:00

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

{{< youtube EeUf7jYVDR0 >}}

## Overview

For air-sealing in attic crawlspaces, a robot should be able to access most of typical narrow locations in the attic crawlspace, carry the tools required for air-sealing (spray gun, sealant can), and precisely apply spray foam sealant to the locations to be sealed. It should be noted that a drone cannot do the job due to the limited payload, and legged robot is not efficient in an attic crawlspace as it needs to grab and hold joists to navigate the attic crawlspace, without touching the ceiling and existing insulations. Our team has built PARIS (Precise Air sealing Robot for Inaccessible Spaces).

Our platform is founded upon a general-purpose multi-track robotic platform. Its flippers are designed to navigate extreme terrains, in both indoor and outdoor environments. PARIS 1.0 is built upon Robot Operating System (ROS) as the middleware that allows a high-level of flexibility and customizability by connecting various sensors and deploying state-of-the-art algorithms. ROS also allows wireless communications via a custom application on a mobile device, which is then used to communicate with human workers

![screen reader text](paris1.jpg)

PARIS’s highly maneuverable multi-track driving system with flippers allows it to traverse over joists and/or uneven surfaces. By controlling its flipper angles, PARIS 1.0 traverse uneven terrains and joists, and easily climbs up 45° inclines. On top of its great mobility, it has a max payload of 88 lbs., allowing it to carry tools and materials for air-sealing.

![screen reader text](paris2.png)
![screen reader text](paris3.png)
![screen reader text](paris4.png)
![screen reader text](paris5.png)

PARIS’ small footprint and driving system makes it a less invasive solution than traditional (human-only) air-sealing efforts, since it minimizes incidental damage like additional holes/cuts for human access. Its light weight also minimizes mess/potential damage to the property when it navigates the attic crawlspace. Learn more about PARIS and our submission to the Department of Energy E-Robot challenge in this short video.
