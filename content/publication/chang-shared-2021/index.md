---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Shared Control Method for Collaborative Human-Robot Plug Task
subtitle: ''
summary: ''
authors:
- Peng Chang
- Rui Luo
- Mehrdad Dorostian
- Taşkın Padır
tags:
- assembly
- Collaboration
- human-robot collaboration
- Physical human-robot interaction
- Plugs
- Robot kinematics
- Robot vision systems
- Robots
- Sockets
- Task analysis
categories: []
date: '2021-10-01'
lastmod: 2022-06-24T16:44:33-04:00
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
publishDate: '2022-06-24T20:44:33.494548Z'
publication_types:
- '2'
abstract: Humans are superior to robots in performing complex assembly tasks primarily
  due to their dexterity and sensorimotor abilities. When humans and robots collaborate
  to complete an assembly task, it is critical to provide the robot with sufficiently
  precise manipulation capabilities and formulate a shared control method that coordinates
  human and robot actions. In this study, we are investigating human-robot collaboration
  in completing an assembly task, namely the plug task. The plug task, motivated by
  the 2015 DARPA Robotics Challenge Finals, involves inserting a plug connected with
  a cable into a paired socket. The human holds the socket while the robot is grasping
  the cable and manages to insert the plug. We estimate an initial socket pose based
  on human subjects' data. With the statistically calculated initial guess, the robot
  could act instantly from the beginning to move the plug towards an initial target.
  The actual socket pose is updated using the Kalman filter in real-time. Besides,
  the system continuously updates the cable model and tracks the plug to enable visual
  servoing to complete the plug task. The result of an extensive experimental study
  demonstrates that the proposed approach demonstrates fast and accurate performance
  as well as flexibility when compared to a state-of-the-art method based on interactive
  probabilistic movement primitives.
publication: '*IEEE Robotics and Automation Letters*'
doi: 10.1109/LRA.2021.3098323
---
