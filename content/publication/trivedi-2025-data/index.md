---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Data-Driven Sampling Based Stochastic MPC for Skid-Steer Mobile Robot Navigation
subtitle: ''
summary: ''
authors:
- Ananya Trivedi
- Sarvesh Prajapati
- Anway Shirgaonkar
- Mark Zolotas
- Taskin Padir
tags: []
categories: []
date: '2025-05-19'
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
publishDate: '2025-05-19T00:00:00Z'
publication_types:
- '1'
abstract: >-
  Traditional approaches to motion modeling for skid-steer robots struggle to capture
  nonlinear tire-terrain dynamics, especially during high-speed maneuvers. In this
  paper, we tackle such nonlinearities by enhancing a dynamic unicycle model with Gaussian
  Process (GP) regression outputs. This enables us to develop an adaptive, uncertainty-informed
  navigation formulation. We solve the resultant stochastic optimal control problem
  using a chance-constrained Model Predictive Path Integral (MPPI) control method. This
  approach formulates obstacle avoidance and path-following as chance constraints, accounting
  for residual uncertainties from the GP to ensure safety and reliability in control.
  Leveraging GPU acceleration, we efficiently manage the non-convex nature of the problem,
  ensuring real-time performance. Our approach unifies path-following and obstacle avoidance
  across different terrains, unlike prior works which typically focus on one or the
  other. We compare our GP-MPPI method against unicycle and data-driven kinematic models
  within the MPPI framework. In simulations, our approach shows superior tracking accuracy
  and obstacle avoidance. We further validate our approach through hardware experiments
  on a skid-steer robot platform, demonstrating its effectiveness in high-speed navigation.
  The GPU implementation of the proposed method and supplementary video footage are
  available at https://stochasticmppi.github.io.
publication: '*2025 IEEE International Conference on Robotics and Automation (ICRA)*'
doi: 10.1109/ICRA55743.2025.11127456
---
