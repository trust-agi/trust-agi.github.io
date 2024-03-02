---
title: "Finding the best not the most: regularized loss minimization subgraph selection for graph classification"
date: 2015-01-01
publishDate: 2019-09-03T11:36:51.701234Z
authors: ["Shirui Pan", "Jia Wu", "Xingquan Zhu", "Guodong Long", "Chengqi Zhang"]
publication_types: ["2"]
abstract: "Classification on structure data, such as graphs, has drawn wide interest in recent years. Due to the lack of explicit features to represent graphs for training classification models, extensive studies have been focused on extracting the most discriminative subgraphs features from the training graph dataset to transfer graphs into vector data. However, such filter-based methods suffer from two major disadvantages: (1) the subgraph feature selection is separated from the model learning process, so the selected most discriminative subgraphs may not best fit the subsequent learning model, resulting in deteriorated classification results; (2) all these methods rely on users to specify the number of subgraph features K, and suboptimally specified K values often result in significantly reduced classification accuracy. In this paper, we propose a new graph classification paradigm which overcomes the above disadvantages by formulating subgraph feature selection as learning a K-dimensional feature space from an implicit and large subgraph space, with the optimal K value being automatically determined. To achieve the goal, we propose a regularized loss minimization-driven (RLMD) feature selection method for graph classification. RLMD integrates subgraph selection and model learning into a unified framework to find discriminative subgraphs with guaranteed minimum loss w.r.t. the objective function. To automatically determine the optimal number of subgraphs K from the exponentially large subgraph space, an effective elastic net and a subgradient method are proposed to derive the stopping criterion, so that K can be automatically obtained once RLMD converges. The proposed RLMD method enjoys gratifying property including proved convergence and applicability to various loss functions. Experimental results on real-life graph datasets demonstrate significant performance gain."
featured: false
publication: "*Pattern Recognition*"
tags: ["Classification", "Feature selection", "Graph classification", "Sparse learning"]
doi: "10.1016/j.patcog.2015.05.019"
---

