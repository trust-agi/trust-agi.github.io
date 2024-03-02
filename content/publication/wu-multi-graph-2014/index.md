---
title: "Multi-graph learning with positive and unlabeled bags"
date: 2014-01-01
publishDate: 2019-09-03T11:36:51.708119Z
authors: ["Jia Wu", "Zhibin Hong", "Shirui Pan", "Xingquan Zhu", "Chengqi Zhang", "Zhihua Cai"]
publication_types: ["1"]
abstract: "In this paper, we formulate a new multi-graph learning task with only positive and unlabeled bags, where labels are only available for bags but not for individual graphs inside the bag. This problem setting raises significant challenges because bag-of-graph setting does not have features to directly represent graph data, and no negative bags exits for deriving discriminative classification models. To solve the challenge, we propose a puMGL learning framework which relies on two iteratively combined processes for multigraph learning: (1) deriving features to represent graphs for learning; and (2) deriving discriminative models with only positive and unlabeled graph bags. For the former, we derive a subgraph scoring criterion to select a set of informative subgraphs to convert each graph into a feature space. To handle unlabeled bags, we assign a weight value to each bag and use the adjusted weight values to select most promising unlabeled bags as negative bags. A margin graph pool (MGP), which contains some representative graphs from positive bags and identified negative bags, is used for selecting subgraphs and training graph classifiers. The iterative subgraph scoring, bag weight updating, and MGP based graph classification forms a closed loop to find optimal subgraphs and most suitable unlabeled bags for multi-graph learning. Experiments and comparisons on real-world multigraph data demonstrate the algorithm performance."
featured: false
publication: "*Proceedings of the 2014 SIAM International Conference on Data Mining*"
doi: "10.1137/1.9781611973440.25"
---

