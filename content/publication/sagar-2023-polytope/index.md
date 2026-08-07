---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Polytope-Based Continuous Scalar Performance Measure With Analytical Gradient
  for Effective Robot Manipulation
subtitle: ''
summary: ''
authors:
- Keerthi Sagar
- Stéphane Caro
- Taskin Padir
- Philip Long
tags: []
categories: []
date: '2023-11-01'
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
publishDate: '2023-11-01T00:00:00Z'
publication_types:
- '2'
abstract: >-
  Performance measures are essential to characterize a robot's ability to carry out
  manipulation tasks. Generally, these measures examine the system's kinematic transformations
  from configuration to task space, but the Capacity margin, a polytope based kinetostatic
  index, provides additionally, both an accurate evaluation of the twist and wrench
  capacities of a robotic manipulator. However, this index is the minimum of a discontinuous
  scalar function leading to difficulties when computing gradients thereby rendering
  it unsuitable for online numerical optimization. In this letter, we propose a novel
  performance index using an approximation of the capacity margin. The proposed index
  is continuous and differentiable, characteristics that are essential for modelling
  smooth and predictable system behavior. We demonstrate its effectiveness in inverse
  kinematics and trajectory optimization application. Moreover, to show its practical
  use, two opposing robot architectures are chosen - (i) Serial robot - Universal Robot-
  UR5 (6-dof); Rethink Robotics- Sawyer Robot (7-dof) and (ii) Parallel manipulator
  - Cable Driven Parallel Robot to validate the results through both simulation and
  experiments. A visual representation of the performance index is also presented.
publication: '*IEEE Robotics and Automation Letters*'
doi: 10.1109/LRA.2023.3313926
---
