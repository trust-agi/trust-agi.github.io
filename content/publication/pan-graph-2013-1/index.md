---
title: "Graph stream classification using labeled and unlabeled graphs"
date: 2013-01-01
publishDate: 2019-09-03T11:36:51.709990Z
authors: ["Shirui Pan", "Xingquan Zhu", "Chengqi Zhang", "Philip S. Yu"]
publication_types: ["1"]
abstract: "Graph classification is becoming increasingly popular due to the rapidly rising applications involving data with structural dependency. The wide spread of the graph applications and the inherent complex relationships between graph objects have made the labels of the graph data expensive and/or difficult to obtain, especially for applications involving dynamic changing graph records. While labeled graphs are limited, the copious amounts of unlabeled graphs are often easy to obtain with trivial efforts. In this paper, we propose a framework to build a stream based graph classification model by combining both labeled and unlabeled graphs. Our method, called gSLU, employs an ensemble based framework to partition graph streams into a number of graph chunks each containing some labeled and unlabeled graphs. For each individual chunk, we propose a minimum-redundancy subgraph feature selection module to select a set of informative subgraph features to build a classifier. To tackle the concept drifting in graph streams, an instance level weighting mechanism is used to dynamically adjust the instance weight, through which the subgraph feature selection can emphasize on difficult graph samples. The classifiers built from different graph chunks form an ensemble for graph stream classification. Experiments on real-world graph streams demonstrate clear benefits of using minimum-redundancy subgraph features to build accurate classifiers. By employing instance level weighting, our graph ensemble model can effectively adapt to the concept drifting in the graph stream for classification."
featured: false
publication: "*ICDE 2013 - 29th International Conference on Data Engineering*"
doi: "10.1109/ICDE.2013.6544842"
---

