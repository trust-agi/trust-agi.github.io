---
title: "Graph ensemble boosting for imbalanced noisy graph stream classification"
date: 2015-01-01
publishDate: 2019-09-03T11:36:51.702061Z
authors: ["Shirui Pan", "Jia Wu", "Xingquan Zhu", "Chengqi Zhang"]
publication_types: ["2"]
abstract: "Many applications involve stream data with structural dependency, graph representations, and continuously increasing volumes. For these applications, it is very common that their class distributions are imbalanced with minority (or positive) samples being only a small portion of the population, which imposes significant challenges for learning models to accurately identify minority samples. This problem is further complicated with the presence of noise, because they are similar to minority samples and any treatment for the class imbalance may falsely focus on the noise and result in deterioration of accuracy. In this paper, we propose a classification model to tackle imbalanced graph streams with noise. Our method, graph ensemble boosting, employs an ensemble-based framework to partition graph stream into chunks each containing a number of noisy graphs with imbalanced class distributions. For each individual chunk, we propose a boosting algorithm to combine discriminative subgraph pattern selection and model learning as a unified framework for graph classification. To tackle concept drifting in graph streams, an instance level weighting mechanism is used to dynamically adjust the instance weight, through which the boosting framework can emphasize on difficult graph samples. The classifiers built from different graph chunks form an ensemble for graph stream classification. Experiments on real-life imbalanced graph streams demonstrate clear benefits of our boosting design for handling imbalanced noisy graph stream."
featured: true
publication: "*IEEE Transactions on Cybernetics*"
tags: ["Data streams", "graph ensemble boosting (gEBoost)", "graphs", "imbalanced class distributions", "noise"]
doi: "10.1109/TCYB.2014.2341031"
---

