---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'constrained_manipulability: A ROS 2 library to Compute and Visualize Constrained
  Capacities for Robotic Manipulators'
subtitle: ''
summary: ''
authors:
- Mark Zolotas
- Philip Long
- Keerthi Sagar
- Taskin Padir
tags: []
categories: []
date: '2025-04-22'
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
publishDate: '2025-04-22T00:00:00Z'
publication_types:
- '2'
abstract: >-
  This paper presents constrained_manipulability, a C++ library to compute and visualize
  a robot manipulator's constrained motion capacities. Manipulability polytopes provide
  a geometrical tool to evaluate the volume of free space surrounding the robotic arm
  when considering both environmental and intrinsic robot constraints, such as collisions
  and joint limits, respectively. Moreover, the polytopes defined by these convex constraints
  represent feasible configurations for the whole robot, that can be utilized in inverse
  kinematics (IK) optimization algorithms to produce collision-free motion trajectories.
  The library is encapsulated in a Robot Operating System (ROS) package. We include
  ROS 1 and ROS 2 implementations of the core C++ library. The constrained_manipulability
  package also heavily depends on our robot_collision_checking package, a ROS interface
  for collision checking via the Flexible Collision Library (FCL).
publication: '*Journal of Open Source Software*'
doi: 10.21105/joss.07481
---
