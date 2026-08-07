---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Socially-Aware Autonomous Doorway Traversal and Payload Delivery for Emergency
  Assistance
subtitle: ''
summary: ''
authors:
- Andrew Snowdy
- Ananya Trivedi
- Sarvesh Prajapati
- Lorena Genua
- Taskin Padir
tags: []
categories: []
date: '2026-07-06'
lastmod: 2026-08-06T00:00:00-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2026-07-06T16:56:00Z'
publication_types:
- '3'
abstract: >-
  In this work, we focus on the scenario of a robot-assisted emergency evacuation.
  We consider two capabilities relevant to such a setting. The first is opening doors
  ahead of the people being evacuated, so that their path toward an exit stays clear.
  The second is retrieving rescue equipment and delivering it to the emergency responders
  carrying out the evacuation. From a systems perspective, this involves several tasks
  at once. The robot must locate ADA-compliant door buttons and the rescue equipment
  it needs to retrieve. Additionally, it must remain aware of the people around it
  and adapt its behavior to them, so that it supports the evacuation rather than getting
  in the way. We address these demands with a behavior tree at the core of our framework.
  This structure is chosen for its ability to select high-level tasks based on environmental
  triggers, and to extend to new situations as they arise. We evaluate the system in
  105 trials on the Toyota Human Support Robot, across five hardware and three simulation
  scenarios. These trials capture the decisions the robot must make in this setting:
  whether to press a door button, yield to a nearby person, walk through a door someone
  else is holding, or first retrieve rescue equipment before traversing the door. Overall,
  the system completes 97 of the 105 trials successfully. These results suggest our
  framework provides a practical basis for robotic assistance in broader emergency
  response tasks. Code and video demonstrations are available at https://github.com/AndrewSnowdy/hsr_mm_control.
publication: '*arXiv preprint arXiv:2607.05315*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2607.05315
url_pdf: https://arxiv.org/pdf/2607.05315
url_code: https://github.com/AndrewSnowdy/hsr_mm_control
---
