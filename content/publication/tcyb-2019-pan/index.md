---
title: "Learning Graph Embedding With Adversarial Training Methods"
date: 2019-09-01
publishDate: 2019-09-05T12:15:49.437666Z
authors: ["Shirui Pan", "Ruiqi Hu", "Sai-Fu Fung", "Guodong Long", "Jing Jiang", "Chengqi Zhang"]
publication_types: ["2"]
abstract: "Graph embedding aims to transfer a graph into vectors to facilitate subsequent graph-analytics tasks like link prediction and graph clustering. Most approaches on graph embedding focus on preserving the graph structure or minimizing the reconstruction errors for graph data. They have mostly overlooked the embedding distribution of the latent codes, which unfortunately may lead to inferior representation in many cases. In this article, we present a novel adversarially regularized framework for graph embedding. By employing the graph convolutional network as an encoder, our framework embeds the topological information and node content into a vector representation, from which a graph decoder is further built to reconstruct the input graph. The adversarial training principle is applied to enforce our latent codes to match a prior Gaussian or uniform distribution. Based on this framework, we derive two variants of the adversarial models, the adversarially regularized graph autoencoder (ARGA) and its variational version, and adversarially regularized variational graph autoencoder (ARVGA), to learn the graph embedding effectively. We also exploit other potential variations of ARGA and ARVGA to get a deeper understanding of our designs. Experimental results that compared 12 algorithms for link prediction and 20 algorithms for graph clustering validate our solutions."
featured: false
publication: "*IEEE Transactions on Cybernetics*"
tags: ["Adversarial regularization", "graph autoencoder", "graph clustering", "graph embedding", "link prediction", "Graph Neural Networks"]
doi: "10.1109/TCYB.2019.2932096"
---

