---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Re4MPC: Reactive Nonlinear MPC for Multi-model Motion Planning via Deep Reinforcement
  Learning'
subtitle: ''
summary: ''
authors:
- Neset Unver Akmandor
- Sarvesh Prajapati
- Mark Zolotas
- Taskin Padir
tags: []
categories: []
date: '2025-08-17'
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
publishDate: '2025-08-17T00:00:00Z'
publication_types:
- '1'
abstract: >-
  Traditional motion planning methods for robots with many degrees-of-freedom, such
  as mobile manipulators, are often computationally prohibitive for real-world settings.
  In this paper, we propose a novel multi-model motion planning pipeline, termed Re4MPC,
  which computes trajectories using Nonlinear Model Predictive Control (NMPC). Re4MPC
  generates trajectories in a computationally efficient manner by reactively selecting
  the model, cost, and constraints of the NMPC problem depending on the complexity
  of the task and robot state. The policy for this reactive decision-making is learned
  via a Deep Reinforcement Learning (DRL) framework. We introduce a mathematical formulation
  to integrate NMPC into this DRL framework. To validate our methodology and design
  choices, we evaluate DRL training and test outcomes in a physics-based simulation
  involving a mobile manipulator. Experimental results demonstrate that Re4MPC is more
  computationally efficient and achieves higher success rates in reaching end-effector
  goals than the NMPC baseline, which computes whole-body trajectories without our
  learning mechanism.
publication: '*2025 IEEE 21st International Conference on Automation Science and Engineering
  (CASE)*'
doi: 10.1109/CASE58245.2025.11164076
---
