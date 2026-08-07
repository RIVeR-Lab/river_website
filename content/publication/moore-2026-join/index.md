---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'JOIN: Anchor-Grasp-Conditioned Joining via Opposition, Inference, and Navigation
  for Bimanual Assistive Manipulation'
subtitle: ''
summary: ''
authors:
- Drake Moore
- Matt Cheng
- Xiang Zhi Tan
- Taskin Padir
tags: []
categories: []
date: '2026-06-09'
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
publishDate: '2026-06-09T17:36:06Z'
publication_types:
- '3'
abstract: >-
  Assistive mobility and manipulation platforms have received increasing attention
  as a means of restoring independence to individuals with disabilities. While effective
  for many basic activities of daily living (ADLs), a significant percentage of everyday
  tasks such as opening a jar, pouring a liquid, lifting a tray, or basic meal preparation,
  is fundamentally bimanual and remains out of reach for any single-arm system. Adding
  a second arm to a wheelchair is impractical, due to the additional power draw, cost,
  and the loss of space required for transfers and mobility. We instead propose a heterogeneous,
  on-demand bimanual system, in which a wheelchair-mounted anchor arm is joined when
  needed by a summoned mobile manipulator that serves as a complement arm. The central
  technical problem, which we call bimanual joining, is conditional: the anchor has
  already committed to a grasp, and the complement arm must choose where to stand and
  what to grasp to complete the task. We formulate bimanual joining as a three-phase
  decomposition (plan, drive, grasp) and show that a vision-language model (VLM), coupled
  with standard geometric tools, provides task-level knowledge sufficient to solve
  a representative class of bimanual ADLs. Our system JOIN, contributes (i) a wheelchair-referenced
  opposition score, and (ii) task-conditioned directional manipulability. We evaluate
  JOIN on a Kinova Gen3 anchor and a Hello Robot Stretch~3 complement on representative
  same-object and different-object tasks. JOIN accomplished more attempts (19/20) than
  state-of-the-art methods (14/20) and required markedly less correction by the operator.
publication: '*arXiv preprint arXiv:2606.11151*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2606.11151
url_pdf: https://arxiv.org/pdf/2606.11151
---

Xiang Zhi Tan and Taşkın Padır share equal advising.
