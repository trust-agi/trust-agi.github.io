---
title: "MGAE: marginalized graph autoencoder for graph clustering"
date: 2017-01-01
publishDate: 2019-09-03T11:36:51.691187Z
authors: ["Chun Wang", "Shirui Pan", "Guodong Long", "Xingquan Zhu", "Jing Jiang"]
publication_types: ["1"]
abstract: "Graph clustering aims to discover community structures in networks, the task being fundamentally challenging mainly because the topology structure and the content of the graphs are dicult to represent for clustering analysis. Recently, graph clustering has moved from traditional shallow methods to deep learning approaches, thanks to the unique feature representation learning capability of deep learning. However, existing deep approaches for graph clustering can only exploit the structure information, while ignoring the content information associated with the nodes in a graph. In this paper, we propose a novel marginalized graph autoencoder (MGAE) algorithm for graph clustering. The key innovation of MGAE is that it advances the autoencoder to the graph domain, so graph representation learning can be carried out not only in a purely unsupervised se.ing by leveraging structure and content information, it can also be stacked in a deep fashion to learn effective representation. From a technical viewpoint, we propose a marginalized graph convolutional network to corrupt network node content, allowing node content to interact with network features, and marginalizes the corrupted features in a graph autoencoder context to learn graph feature representations. The learned features are fed into the spectral clustering algorithm for graph clustering. Experimental results on benchmark datasets demonstrate the superior performance of MGAE, compared to numerous baselines."
featured: false
publication: "*CIKM'17 - Proceedings of the 2017 ACM Conference on Information and Knowledge Management*"
tags: ["Autoencoder", "Graph autoencoder", "Graph clustering", "Graph convolutional network", "Network representation"]
doi: "10.1145/3132847.3132967"
---

