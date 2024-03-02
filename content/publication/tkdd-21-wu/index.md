---
title: "Learning Graph Neural Networks with Positive and Unlabeled Nodes"
date: 2021-02-07
publishDate: 2020-02-07T12:19:12.824998Z
authors: ["Man Wu", "Shirui Pan", "Lan Du", "Xingquan Zhu"]
publication_types: ["2"]
abstract: "Graph neural networks (GNNs) are important tools for transductive learning tasks, such as node classification in graphs, due to their expressive power in capturing complex interdependency between nodes. To enable graph neural network learning, existing works typically assume that labeled nodes, from two or multiple classes, are provided, so that a discriminative classifier can be learned from the labeled data. In reality, this assumption might be too restrictive for applications, as users may only provide labels of interest in a single class for a small number of nodes. In addition, most GNN models only aggregate information from short distances (e.g., 1-hop neighbors) in each round, and fail to capture long distance relationship in graphs. In this paper, we propose a novel graph neural network framework, long-short distance aggregation networks (LSDAN), to overcome these limitations. By generating multiple graphs at different distance levels, based on the adjacency matrix, we develop a long-short distance attention model to model these graphs. The direct neighbors are captured via a short-distance attention mechanism, and neighbors with long distance are captured by a long distance attention mechanism. Two novel risk estimators are further employed to aggregate long- short-distance networks, for PU learning and the loss is back-propagated for model learning. Experimental results on real-world datasets demonstrate the effectiveness of our algorithm."
featured: false
publication: "ACM Transactions on Knowledge Discovery from Data (TKDD)"
tags: ["Graph Neural Networks", "Positive Unlabeled Learning"]
url_pdf: https://arxiv.org/pdf/2103.04683.pdf
---
