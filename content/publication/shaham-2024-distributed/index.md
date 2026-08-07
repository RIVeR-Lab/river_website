---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Distributed Model Predictive Control for Heterogeneous Platoons with Affine
  Spacing Policies and Arbitrary Communication Topologies
subtitle: ''
summary: ''
authors:
- Michael Shaham
- Taskin Padir
tags: []
categories: []
date: '2024-09-24'
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
publishDate: '2024-09-24T00:00:00Z'
publication_types:
- '1'
abstract: >-
  This paper presents a distributed model predictive control (DMPC) algorithm for a
  heterogeneous platoon using arbitrary communication topologies, provided each vehicle
  can communicate with a preceding vehicle in the platoon. The proposed DMPC algorithm
  can accommodate any spacing policy that is affine in a vehicle's velocity, which
  includes constant distance or constant time headway spacing policies. By analyzing
  the total cost for the entire platoon, a sufficient condition is derived to ensure
  platoon asymptotic stability. Simulation experiments with a platoon of 50 vehicles
  and hardware experiments with a platoon of four 1/10th-scale vehicles validate the
  algorithm and compare performance under different spacing policies and communication
  topologies. Code for the experiments and a video demonstration of the hardware experiment
  can be found at https://www.github.com/river-lab/dmpc_itsc_2024.git.
publication: '*2024 IEEE 27th International Conference on Intelligent Transportation
  Systems (ITSC)*'
doi: 10.1109/ITSC58415.2024.10920120
---
