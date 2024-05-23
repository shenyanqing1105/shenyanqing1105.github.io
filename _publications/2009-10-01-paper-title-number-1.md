---
title: "TCL: Tightly Coupled Learning Strategy for Weakly Supervised Hierarchical Place Recognition"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: '**Yanqing Shen**, Ruotong Wang, Weiliang Zuo, Nanning Zheng*'
date: 2022-01-10
venue: 'IEEE Robotics and Automation Letters'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9676481'
---

Visual place recognition (VPR) is a key issue for robotics and autonomous systems. For the trade-off between time and performance, most of methods use the coarse-to-fine hierarchical architecture, which consists of retrieving top-N candidates using global features, and re-ranking top-N with local features. However, since the two types of features are usually processed independently, re-ranking may harm global retrieval, termed re-ranking confusion . Moreover, re-ranking is limited by global retrieval. In this paper, we propose a tightly coupled learning (TCL) strategy to train triplet models. Different from original triplet learning (OTL) strategy, it combines global and local descriptors for joint optimization. In addition, a bidirectional search dynamic time warping (BS-DTW) algorithm is also proposed to mine locally spatial information tailored to VPR in re-ranking. The experimental results on public benchmarks show that the models using TCL outperform the models using OTL, and TCL can be used as a general strategy to improve performance for weakly supervised ranking tasks. Further, our lightweight unified model is better than several state-of-the-art methods and has over an order of magnitude of computational efficiency to meet the real-time requirements of robots.
