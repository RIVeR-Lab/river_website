---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Multimodal Fusion of EMG and Vision for Human Grasp Intent Inference in Prosthetic
  Hand Control
subtitle: ''
summary: ''
authors:
- Mehrshad Zandigohar
- Mo Han
- Mohammadreza Sharif
- Sezen Yagmur Gunay
- Mariusz P. Furmanek
- Mathew Yarossi
- Paolo Bonato
- Cagdas Onal
- Taskin Padir
- Deniz Erdogmus
- Gunar Schirner
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Human-Computer Interaction
- Computer Science - Robotics
- Electrical Engineering and Systems Science - Signal Processing
- I.2.9
- I.5.4
categories: []
date: '2022-04-01'
lastmod: 2022-06-24T16:44:32-04:00
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
publishDate: '2022-06-24T20:44:32.801724Z'
publication_types:
- '0'
abstract: For lower arm amputees, robotic prosthetic hands offer the promise to regain
  the capability to perform fine object manipulation in activities of daily living.
  Current control methods based on physiological signals such as EEG and EMG are prone
  to poor inference outcomes due to motion artifacts, variability of skin electrode
  junction impedance over time, muscle fatigue, and other factors. Visual evidence
  is also susceptible to its own artifacts, most often due to object occlusion, lighting
  changes, variable shapes of objects depending on view-angle, among other factors.
  Multimodal evidence fusion using physiological and vision sensor measurements is
  a natural approach due to the complementary strengths of these modalities. In this
  paper, we present a Bayesian evidence fusion framework for grasp intent inference
  using eye-view video, gaze, and EMG from the forearm processed by neural network
  models. We analyze individual and fused performance as a function of time as the
  hand approaches the object to grasp it. For this purpose, we have also developed
  novel data processing and augmentation techniques to train neural network components.
  Our experimental data analyses demonstrate that EMG and visual evidence show complementary
  strengths, and as a consequence, fusion of multimodal evidence can outperform each
  individual evidence modality at any given time. Specifically, results indicate that,
  on average, fusion improves the instantaneous upcoming grasp type classification
  accuracy while in the reaching phase by 13.66% and 14.8%, relative to EMG and visual
  evidence individually, resulting in an overall fusion accuracy of 95.3%.
publication: '*arXiv*'
doi: 10.48550/arXiv.2104.03893
links:
- name: URL
  url: http://arxiv.org/abs/2104.03893
---
