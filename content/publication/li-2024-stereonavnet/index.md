---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'StereoNavNet: Learning to Navigate using Stereo Cameras with Auxiliary Occupancy
  Voxels'
subtitle: ''
summary: ''
authors:
- Hongyu Li
- Taskin Padir
- Huaizu Jiang
tags: []
categories: []
date: '2024-10-14'
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
publishDate: '2024-10-14T00:00:00Z'
publication_types:
- '1'
abstract: >-
  Visual navigation has received significant attention recently. Most of the prior
  works focus on predicting navigation actions based on semantic features extracted
  from visual encoders. However, these approaches often rely on large datasets and
  exhibit limited generalizability. In contrast, our approach draws inspiration from
  traditional navigation planners that operate on geometric representations, such as
  occupancy maps. We propose StereoNavNet (SNN), a novel visual navigation approach
  employing a modular learning framework comprising perception and policy modules.
  Within the perception module, we estimate an auxiliary 3D voxel occupancy grid from
  stereo RGB images and extract geometric features from it. These features, along with
  user-defined goals, are utilized by the policy module to predict navigation actions.
  Through extensive empirical evaluation, we demonstrate that SNN outperforms baseline
  approaches in terms of success rates, success weighted by path length, and navigation
  error. Furthermore, SNN exhibits better generalizability, characterized by maintaining
  leading performance when navigating across previously unseen environments.
publication: '*2024 IEEE/RSJ International Conference on Intelligent Robots and Systems
  (IROS)*'
doi: 10.1109/IROS58592.2024.10802385
---
