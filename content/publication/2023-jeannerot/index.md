---
# Documentation: https://hugoblox.com/docs/managing-content/

title: Mitigating User Identification Errors in Resource Optimization for Grant-Free
  Random Access
subtitle: ''
summary: ''
authors:
- Alix Jeannerot
- Malcolm Egan
- Lélio Chetot
- Jean-Marie Gorce
tags: []
categories: []
date: '2023-06-01'
lastmod: 2024-01-19T17:31:22+01:00
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
publishDate: '2024-01-19T16:31:22.022863Z'
publication_types:
- '1'
abstract: In grant-free random access, a key question is how devices should utilize
  resources without coordination. One standard solution to this problem are strategies
  where devices randomly select time-slots based on an optimized stochastic allocation
  rule. However, the optimization of this allocation rule requires accurate knowledge
  of which devices have been active in previous frames. As user identification algorithms
  are subject to errors, the expected throughput of the optimized allocation can be
  highly suboptimal. In this paper, we propose algorithms for optimization of device
  time-slot allocations that mitigate the impact of user identification errors. We
  show that when the activity distribution with and without errors is known, then
  our algorithm converges with probability one to a stationary point. When the activity
  distributions are not available, we introduce new theoretically-motivated heuristics
  which significantly improve the expected throughput over existing algorithms and
  approach the performance when errors are not present.
publication: '*2023 IEEE 97th Vehicular Technology Conference (VTC2023-Spring)*'
doi: 10.1109/VTC2023-Spring57618.2023.10200062
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10200062/
---
