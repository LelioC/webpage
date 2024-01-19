---
# Documentation: https://hugoblox.com/docs/managing-content/

title: Activity models and Bayesian estimation algorithms for wireless grant-free
  random access
subtitle: ''
summary: ''
authors:
- Lélio Chetot
tags: []
categories: []
date: '2022-07-01'
lastmod: 2024-01-19T17:31:21+01:00
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
publishDate: '2024-01-19T16:31:21.409595Z'
publication_types:
- '7'
abstract: The new 5G’s wireless networks have started to be deployed all around the
  world. With them, a large spectrum of services are about to emerge, resulting in
  new stringent requirements so that 5G targets performances exceed that of 4G by
  a factor of 10. The services are enhanced mobile broadband (eMBB), ultra reliable
  and low-latency communication (uRLLC) and massive machine-type communication (mMTC)
  where each of which has required the ongoing development of key new technologies.
  Many of these technologies will also play an important role in the emergence of
  6G. In this thesis, the focus is on grant-free RA (GFRA) as an enabler of uRLLC
  and mMTC. GFRA is a new protocol introduced in 5G new radio (5G-NR) for reducing
  the data overhead of the random access (RA) procedure. This results in a significant
  reduction in the latencies of the user equipments (UEs) access to a connected medium
  via an access point (AP). Achieving efficient GFRA is of key importance for many
  5G applications, e.g. for large scale internet of things (IoT) wireless networks.
  The study of new non-orthogonal multiple access (NOMA) signal processing techniques
  is then considered. Using tools from the theory of Bayesian compressed sensing (CS),
  algorithms within the family of approximate message passing (AMP) are developed
  to address the joint active user detection and channel estimation (AUDaCE) problem.
  It is crucial to properly identify transmitting UEs and guarantee that an AP can
  reliably transmit back data to the detected UEs. In contrast to existing work on
  this topic, the AUDaCE is studied for wireless networks where the activity of the
  UEs is correlated. To this end, two activity models are introduced. The first one
  models the activity of the UEs in the network with group-homogeneous activity (GHomA).
  The second model accounts for more general dependence structure via group-heterogeneous
  activity (GHetA). Approximate message passing algorithms within the hybrid GAMP
  (HGAMP) framework are developed for each of the models. With the aid of latent variables
  associated to each group for modeling the activity probabilities of the UEs, the
  GHomA-HGAMP algorithm can perform AUDaCE for GFRA leveraging such a group homogeneity.
  When the activity is heterogenous, it is possible to develop GHetA-HGAMP using the
  copula theory. Extensive numerical studies are performed, which highlight significant
  performance improvements of GHomA-HGAMP and GHetA-HGAMP over existing algorithms
  which do not properly account for correlated activity. In particular, the channel
  estimation and active user detection capability are enhanced in many scenarios with
  up to a 4dB improvement with twice less user errors. As a whole, this thesis provides
  a systematic approach to AUDaCE for wireless networks with correlated activities
  using Bayesian CS.
publication: ''
links:
- name: URL
  url: https://theses.hal.science/tel-03871656
---
