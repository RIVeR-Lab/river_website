---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Tactile Pose Estimation and Policy Learning for Unknown Object Manipulation
subtitle: ''
summary: ''
authors:
- Tarik Kelestemur
- Robert Platt
- Taskin Padir
tags:
- Computer Science - Robotics
categories: []
date: '2022-03-01'
lastmod: 2022-06-24T16:44:34-04:00
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
publishDate: '2022-06-24T20:44:33.933460Z'
publication_types:
- '0'
abstract: Object pose estimation methods allow finding locations of objects in unstructured
  environments. This is a highly desired skill for autonomous robot manipulation as
  robots need to estimate the precise poses of the objects in order to manipulate
  them. In this paper, we investigate the problems of tactile pose estimation and
  manipulation for category-level objects. Our proposed method uses a Bayes filter
  with a learned tactile observation model and a deterministic motion model. Later,
  we train policies using deep reinforcement learning where the agents use the belief
  estimation from the Bayes filter. Our models are trained in simulation and transferred
  to the real world. We analyze the reliability and the performance of our framework
  through a series of simulated and real-world experiments and compare our method
  to the baseline work. Our results show that the learned tactile observation model
  can localize the pose of novel objects at 2-mm and 1-degree resolution for position
  and orientation, respectively. Furthermore, we experiment on a bottle opening task
  where the gripper needs to reach the desired grasp state.
publication: '*arXiv*'
doi: 10.48550/arXiv.2203.10685
links:
- name: URL
  url: http://arxiv.org/abs/2203.10685
---
