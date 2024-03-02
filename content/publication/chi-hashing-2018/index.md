---
title: "Hashing for adaptive real-time graph stream classification with concept drifts"
date: 2018-01-01
publishDate: 2019-09-03T11:36:51.683963Z
authors: ["Lianhua Chi", "Bin Li", "Xingquan Zhu", "Shirui Pan", "Ling Chen"]
publication_types: ["2"]
abstract: "Many applications involve processing networked streaming data in a timely manner. Graph stream classification aims to learn a classification model from a stream of graphs with only one-pass of data, requiring real-time processing in training and prediction. This is a nontrivial task, as many existing methods require multipass of the graph stream to extract subgraph structures as features for graph classification which does not simultaneously satisfy 'one-pass' and 'real-time' requirements. In this paper, we propose an adaptive real-time graph stream classification method to address this challenge. We partition the unbounded graph stream data into consecutive graph chunks, each consisting of a fixed number of graphs and delivering a corresponding chunk-level classifier. We employ a random hashing function to compress the original node set of graphs in each chunk for fast feature detection when training chunk-level classifiers. Furthermore, a differential hashing strategy is applied to map unlimited increasing features (i.e., cliques) into a fixed-size feature space which is then used as a feature vector for stochastic learning. Finally, the chunk-level classifiers are weighted in an ensemble learning model for graph classification. The proposed method substantially speeds up the graph feature extraction and avoids unbounded graph feature growth. Moreover, it effectively offsets concept drifts in graph stream classification. Experiments on real-world and synthetic graph streams demonstrate that our method significantly outperforms existing methods in both classification accuracy and learning efficiency."
featured: false
publication: "*IEEE Transactions on Cybernetics*"
tags: ["Cliques", "concept drifts", "graph stream classification", "hashing"]
doi: "10.1109/TCYB.2017.2708979"
---

