---
title: "Long-short Distance Aggregation Networks for Positive Unlabeled Graph Learning"
date: 2019-09-01
publishDate: 2019-09-05T12:19:12.827085Z
authors: ["Man Wu", "Shirui Pan", "Lan Du", "Ivor W., Tsang", "Bo Du"]
publication_types: ["1"]
abstract: "Graph neural nets are emerging tools to represent network nodes for classification. However, existing approaches typically suffer from two limitations: (1) they only aggregate information from short distance (e.g., 1-hop neighbors) each round and fail to capture long distance relationship in graphs; (2) they require users to label data from several classes to facilitate the learning of discriminative models; whereas in reality, users may only provide labels of a small number of nodes in a single class. To overcome these limitations, this paper presents a novel long-short distance aggregation networks (LSDAN) for positive unlabeled (PU) graph learning. Our theme is to generate multiple graphs at different distances based on the adjacency matrix, and further develop a long-short distance attention model for these graphs. The short-distance attention mechanism is used to capture the importance of neighbor nodes to a target node. The long-distance attention mechanism is used to capture the propagation of information within a localized area of each node and help model weights of different graphs for node representation learning. A non-negative risk estimator is further employed, to aggregate long- short-distance networks, for PU learning using back-propagated loss modeling. Experiments on real-world datasets validate the effectiveness of our approach."
featured: false
publication: "*CIKM'19 - Proceedings of the 2019 ACM Conference on Information and Knowledge Management*"
tags: ["Graph Neural Networks"]
---

