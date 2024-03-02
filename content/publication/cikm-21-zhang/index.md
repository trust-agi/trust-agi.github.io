---
title: "Projective Ranking: A Transferable Evasion Attack Method on Graph Neural Networks"
date: 2021-08-09
publishDate: 2021-08-09T12:15:49.436331Z
authors: ["He Zhang", "Bang Wu", "Xiangwen Yang", "Chuan Zhou", "Shuo Wang", "Xingliang Yuan", "Shirui Pan"]
publication_types: ["1"]
abstract: "Graph Neural Networks (GNNs) have emerged as a series of effective learning methods for graph-related tasks. However, GNNs are shown vulnerable to adversarial attacks, where attackers can fool GNNs into making wrong predictions on adversarial samples with well-designed perturbations. Specifically, we observe that the current evasion attacks suffer from two limitations: (1) the attack strategy based on the reinforcement learning method might not be transferable when the attack budget changes; (2) the greedy mechanism in the vanilla gradient-based method ignores the long-term benefits of each perturbation operation. In this paper, we propose a new attack method named projective ranking to overcome the above limitations. Our idea is to learn a powerful attack strategy considering the long-term benefits of perturbations, then adjust it as little as possible to generate adversarial samples under different budgets. We further employ mutual information to measure the long-term benefits of each perturbation and rank them accordingly, so the learned attack strategy has better attack performance. Our method dramatically reduces the adaptation cost of learning a new attack strategy by projecting the attack strategy when the attack budget changes. Our preliminary evaluation results in synthesized and real-world datasets demonstrate that our method owns powerful attack performance and effective transferability."
featured: false
publication: "*Proceedings of the 30th ACM International Conference on Information and Knowledge Management (CIKM'21), November 1--5, 2021, Virtual Event, QLD, Australia*"
tags: ["Graph Neural Networks", "Adversarial Attacks"]
---
