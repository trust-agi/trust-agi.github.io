---
title: "CogBoost: boosting for fast cost-sensitive graph classification"
date: 2015-01-01
publishDate: 2019-09-03T11:36:51.700643Z
authors: ["Shirui Pan", "Jia Wu", "Xingquan Zhu"]
publication_types: ["2"]
abstract: "Graph classification has drawn great interests in recent years due to the increasing number of applications involving objects with complex structure relationships. To date, all existing graph classification algorithms assume, explicitly or implicitly, that misclassifying instances in different classes incurs an equal amount of cost (or risk), which is often not the case in real-life applications (where misclassifying a certain class of samples, such as diseased patients, is subject to more expensive costs than others). Although cost-sensitive learning has been extensively studied, all methods are based on data with instance-feature representation. Graphs, however, do not have features available for learning and the feature space of graph data is likely infinite and needs to be carefully explored in order to favor classes with a higher cost. In this paper, we propose, CogBoost, a fast cost-sensitive graph classification algorithm, which aims to minimize the misclassification costs (instead of the errors) and achieve fast learning speed for large scale graph data sets. To minimize the misclassification costs, CogBoost iteratively selects the most discriminative subgraph by considering costs of different classes, and then solves a linear programming problem in each iteration by using Bayes decision rule based optimal loss function. In addition, a cutting plane algorithm is derived to speed up the solving of linear programs for fast learning on large scale data sets. Experiments and comparisons on real-world large graph data sets demonstrate the effectiveness and the efficiency of our algorithm."
featured: true
publication: "*IEEE Transactions on Knowledge and Data Engineering*"
tags: ["Graph classification", "boosting", "cost-sensitive learning", "cutting plane algorithm", "large scale graphs", "subgraphs"]
doi: "10.1109/TKDE.2015.2391115"
---

