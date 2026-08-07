---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Probabilistic Motion Model for Skid-Steer Wheeled Mobile Robot Navigation
  on Off-Road Terrains
subtitle: ''
summary: ''
authors:
- Ananya Trivedi
- Mark Zolotas
- Ali Adeeb Abbas
- Sarvesh Prajapati
- Salah Bazzi
- Taskin Padir
tags: []
categories: []
date: '2024-05-13'
lastmod: 2026-08-07T00:00:00-04:00
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
publishDate: '2024-05-13T00:00:00Z'
publication_types:
- '1'
abstract: >-
  Skid-Steer Wheeled Mobile Robots (SSWMRs) are increasingly being used for off-road
  autonomy applications. When turning at high speeds, these robots tend to undergo
  significant skidding and slipping. In this work, using Gaussian Process Regression
  (GPR) and Sigma-Point Transforms, we estimate the non-linear effects of tire-terrain
  interaction on robot velocities in a probabilistic fashion. Using the mean estimates
  from GPR, we propose a data-driven dynamic motion model that is more accurate at
  predicting future robot poses than conventional kinematic motion models. By efficiently
  solving a convex optimization problem based on the history of past robot motion,
  the GPR augmented motion model generalizes to previously unseen terrain conditions.
  The output distribution from the proposed motion model can be used for local motion
  planning approaches, such as stochastic model predictive control, leveraging model
  uncertainty to make safe decisions. We validate our work on a benchmark real-world
  multi-terrain SSWMR dataset. Our results show that the model generalizes to three
  different terrains while significantly reducing errors in linear and angular motion
  predictions. As shown in the attached video, we perform a separate set of experiments
  on a physical robot to demonstrate the robustness of the proposed algorithm.
publication: '*2024 IEEE International Conference on Robotics and Automation (ICRA)*'
doi: 10.1109/ICRA57147.2024.10611343
---
