---
title: "Graph Stochastic Neural Networks for Semi-supervised Learning"
date: 2020-09-25
publishDate: 2020-09-25T12:19:12.824998Z
authors: ["Haibo Wang", "Chuan Zhou", "Xin Chen", "Jia Wu", "Shirui Pan", "Jilong Wang"]
publication_types: ["1"]
abstract: "Graph Neural Networks (GNNs) have achieved remarkable performance in the task of the semi-supervised node classification. However, most existing models learn a deterministic classification function, which lack sufficient flexibility to explore better choices in the presence of kinds of imperfect observed data such as the scarce labeled nodes and noisy graph structure. To improve the rigidness and inflexibility of deterministic classification functions, this paper proposes a novel framework named Graph Stochastic Neural Networks (GSNN), which aims to model the uncertainty of the classification function by simultaneously learning a family of functions, i.e., a stochastic function. Specifically, we introduce a learnable graph neural network coupled with a high-dimensional latent variable to model the distribution of the classification function, and further adopt the amortised variational inference to approximate the intractable joint posterior for missing labels and the latent variable. By maximizing the lower-bound of the likelihood for observed node labels, the instantiated models can be trained in an end-to-end manner effectively. Extensive experiments on three real-world datasets show that GSNN achieves substantial performance gain in different scenarios compared with stat-of-the-art baselines."
featured: false
publication: "*Thirty-fourth Conference on Neural Information Processing Systems, NeurIPS-20*"
tags: ["Graph Neural Networks"]
---
