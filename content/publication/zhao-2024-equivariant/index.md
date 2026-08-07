---
# Documentation: https://wowchemy.com/docs/managing-content/

title: E(2)-Equivariant Graph Planning for Navigation
subtitle: ''
summary: ''
authors:
- Linfeng Zhao
- Hongyu Li
- Taskin Padir
- Huaizu Jiang
- Lawson L. S. Wong
tags: []
categories: []
date: '2024-04-01'
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
publishDate: '2024-04-01T00:00:00Z'
publication_types:
- '2'
abstract: >-
  Learning for robot navigation presents a critical and challenging task. The scarcity
  and costliness of real-world datasets necessitate efficient learning approaches.
  In this letter, we exploit Euclidean symmetry in planning for 2D navigation, which
  originates from Euclidean transformations between reference frames and enables parameter
  sharing. To address the challenges of unstructured environments, we formulate the
  navigation problem as planning on a geometric graph and develop an equivariant message
  passing network to perform value iteration. Furthermore, to handle multi-camera input,
  we propose a learnable equivariant layer to lift features to a desired space. We
  conduct comprehensive evaluations across five diverse tasks encompassing structured
  and unstructured environments, along with maps of known and unknown, given point
  goals or semantic goals. Our experiments confirm the substantial benefits on training
  efficiency, stability, and generalization.
publication: '*IEEE Robotics and Automation Letters*'
doi: 10.1109/LRA.2024.3360011
---
