---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'robot_collision_checking: A Lightweight ROS 2 Interface to FCL (Flexible Collision
  Library)'
subtitle: ''
summary: ''
authors:
- Mark Zolotas
- Philip Long
- Taskin Padir
tags: []
categories: []
date: '2025-01-27'
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
publishDate: '2025-01-27T00:00:00Z'
publication_types:
- '2'
abstract: >-
  This paper presents robot_collision_checking, a C++ library that provides a Robot
  Operating System (ROS) interface to the Flexible Collision Library (FCL) for typical
  robotics applications. FCL is an open-source C++ library that provides efficient
  collision detection and distance computation for 3D environments. While these capabilities
  are crucial in robotics to ensure safety and enable effective motion planning, FCL
  is not readily available for many robot architectures built atop ROS. Given that
  the robotics community widely relies on ROS as the standard for software development,
  it would greatly benefit from a lightweight ROS interface to FCL. The robot_collision_checking
  package fulfils this demand by exposing FCL functionality to ROS message types, thereby
  allowing robotics researchers and practitioners that rely on ROS to easily access
  the collision and distance checking features of FCL.
publication: '*Journal of Open Source Software*'
doi: 10.21105/joss.07473
---
