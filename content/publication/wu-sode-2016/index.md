---
title: "SODE: Self-adaptive one-dependence estimators for classification"
date: 2016-01-01
publishDate: 2019-09-03T11:36:51.698756Z
authors: ["Jia Wu", "Shirui Pan", "Xingquan Zhu", "Peng Zhang", "Chengqi Zhang"]
publication_types: ["2"]
abstract: "SuperParent-One-Dependence Estimators (SPODEs) represent a family of semi-naive Bayesian classifiers which relax the attribute independence assumption of Naive Bayes (NB) to allow each attribute to depend on a common single attribute (superparent). SPODEs can effectively handle data with attribute dependency but still inherent NB's key advantages such as computational efficiency and robustness for high dimensional data. In reality, determining an optimal superparent for SPODEs is difficult. One common approach is to use weighted combinations of multiple SPODEs, each having a different superparent with a properly assigned weight value (i.e., a weight value is assigned to each attribute). In this paper, we propose a self-adaptive SPODEs, namely SODE, which uses immunity theory in artificial immune systems to automatically and self-adaptively select the weight for each single SPODE. SODE does not need to know the importance of individual SPODE nor the relevance among SPODEs, and can flexibly and efficiently search optimal weight values for each SPODE during the learning process. Extensive experiments and comparisons on 56 benchmark data sets, and validations on image and text classification, demonstrate that SODE outperforms state-of-the-art weighted SPODE algorithms and is suitable for a wide range of learning tasks. Results also confirm that SODE provides an appropriate balance between runtime efficiency and accuracy."
featured: false
publication: "*Pattern Recognition*"
tags: ["Classification", "Artificial immune systems", "Attribute weighting", "Evolutionary machine learning", "Naive Bayes", "Self-adaptive"]
doi: "10.1016/j.patcog.2015.08.023"
---

