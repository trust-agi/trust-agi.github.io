---
title: "Boosting for multi-graph classification"
date: 2015-01-01
publishDate: 2019-09-03T11:36:51.700057Z
authors: ["Jia Wu", "Shirui Pan", "Xingquan Zhu", "Zhihua Cai"]
publication_types: ["2"]
abstract: "In this paper, we formulate a novel graph-based learning problem, multi-graph classification (MGC), which aims to learn a classifier from a set of labeled bags each containing a number of graphs inside the bag. A bag is labeled positive, if at least one graph in the bag is positive, and negative otherwise. Such a multi-graph representation can be used for many real-world applications, such as webpage classification, where a webpage can be regarded as a bag with texts and images inside the webpage being represented as graphs. This problem is a generalization of multi-instance learning (MIL) but with vital differences, mainly because instances in MIL share a common feature space whereas no feature is available to represent graphs in a multi-graph bag. To solve the problem, we propose a boosting based multi-graph classification framework (bMGC). Given a set of labeled multi-graph bags, bMGC employs dynamic weight adjustment at both bag- and graph-levels to select one subgraph in each iteration as a weak classifier. In each iteration, bag and graph weights are adjusted such that an incorrectly classified bag will receive a higher weight because its predicted bag label conflicts to the genuine label, whereas an incorrectly classified graph will receive a lower weight value if the graph is in a positive bag (or a higher weight if the graph is in a negative bag). Accordingly, bMGC is able to differentiate graphs in positive and negative bags to derive effective classifiers to form a boosting model for MGC. Experiments and comparisons on real-world multi-graph learning tasks demonstrate the algorithm performance."
featured: false
publication: "*IEEE Transactions on Cybernetics*"
tags: ["graph classification", "subgraph mining", "Boosting", "multi-graph", "multi-instance learning"]
doi: "10.1109/TCYB.2014.2327111"
---

