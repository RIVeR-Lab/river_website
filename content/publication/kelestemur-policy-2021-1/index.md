---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Policy Learning for Visually Conditioned Tactile Manipulation
subtitle: ''
summary: ''
authors:
- Tarik Kelestemur
- Taşkın Padır
- Robert Platt
tags:
- Navigation
- Recurrent neural networks
- Reinforcement learning
- Robot learning
- Simulation
- Tactile sensors
- Visualization
categories: []
date: '2021-09-01'
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
publishDate: '2022-06-24T20:44:33.759517Z'
publication_types:
- '1'
abstract: Recent work on robot learning with visual observations has shown great success
  in solving many manipulation tasks. While visual observations contain rich information
  about the environment and the robot, they can be unreliable in the presence of visual
  noise or occlusions. In these cases, we can leverage tactile observations generated
  by the interaction between the robot and the environment. In this paper, we propose
  a framework for learning manipulation policies that fuse visual and tactile feedback.
  The control problems considered in this work are to localize a gripper with respect
  to the environment image and navigate to desired states. Our method uses a learned
  Bayes filter to estimate the state of a gripper by conditioning the tactile observations
  on the environment image. We use deep reinforcement learning for solving the localization
  and navigation problems provided with the belief of the grippertextquoterights state
  and the environment image. We compare our method against two baselines where the
  agent uses tactile observation directly with a recurrent neural network or uses
  a point estimate of the state instead of the full belief state. We also transfer
  the policies to the real world and validate them on a physical robot.
publication: '*2021 IEEE/RSJ International Conference on Intelligent Robots and Systems
  (IROS)*'
doi: 10.1109/IROS51168.2021.9636866
---
