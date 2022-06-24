---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Reactive Navigation Framework for Mobile Robots by Heuristically Evaluated
  Pre-sampled Trajectories
subtitle: ''
summary: ''
authors:
- Neşet Ünver Akmandor
- Taşkın Padır
tags:
- Computer Science - Robotics
categories: []
date: '2021-05-01'
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
publishDate: '2022-06-24T20:44:32.974383Z'
publication_types:
- '4'
abstract: This paper describes and analyzes a reactive navigation framework for mobile
  robots in unknown environments. The approach does not rely on a global map and only
  considers the local occupancy in its robot-centered 3D grid structure. The proposed
  algorithm enables fast navigation by heuristic evaluations of pre-sampled trajectories
  on-the-fly. At each cycle, these paths are evaluated by a weighted cost function,
  based on heuristic features such as closeness to the goal, previously selected trajectories,
  and nearby obstacles. This paper introduces a systematic method to calculate a feasible
  pose on the selected trajectory, before sending it to the controller for the motion
  execution. Defining the structures in the framework and providing the implementation
  details, the paper also explains how to adjust its offline and online parameters.
  To demonstrate the versatility and adaptability of the algorithm in unknown environments,
  physics-based simulations on various maps are presented. Benchmark tests show the
  superior performance of the proposed algorithm over its previous iteration and another
  state-of-art method. The open-source implementation of the algorithm and the benchmark
  data can be found at urlhttps://github.com/RIVeR-Lab/tentabot.
publication: ''
links:
- name: URL
  url: https://ui.adsabs.harvard.edu/abs/2021arXiv210508145U
---
