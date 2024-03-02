---
title: "Boosting for graph classification with universum"
date: 2017-01-01
publishDate: 2019-09-03T11:36:51.689618Z
authors: ["Shirui Pan", "Jia Wu", "Xingquan Zhu", "Guodong Long", "Chengqi Zhang"]
publication_types: ["2"]
abstract: "Recent years have witnessed extensive studies of graph classification due to the rapid increase in applications involving structural data and complex relationships. To support graph classification, all existing methods require that training graphs should be relevant (or belong) to the target class, but cannot integrate graphs irrelevant to the class of interest into the learning process. In this paper, we study a new universum graph classification framework which leverages additional “non-example” graphs to help improve the graph classification accuracy. We argue that although universum graphs do not belong to the target class, they may contain meaningful structure patterns to help enrich the feature space for graph representation and classification. To support universum graph classification, we propose a mathematical programming algorithm, ugBoost, which integrates discriminative subgraph selection and margin maximization into a unified framework to fully exploit the universum. Because informative subgraph exploration in a universum setting requires the search of a large space, we derive an upper bound discriminative score for each subgraph and employ a branch-and-bound scheme to prune the search space. By using the explored subgraphs, our graph classification model intends to maximize the margin between positive and negative graphs and minimize the loss on the universum graph examples simultaneously. The subgraph exploration and the learning are integrated and performed iteratively so that each can be beneficial to the other. Experimental results and comparisons on real-world dataset demonstrate the performance of our algorithm."
featured: false
publication: "*Knowledge and Information Systems*"
tags: ["Boosting", "Graph classification", "Graph mining", "Supervised learning", "Universum"]
doi: "10.1007/s10115-016-0934-z"
---

