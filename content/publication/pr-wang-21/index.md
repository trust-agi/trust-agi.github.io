---
title: "Deep Neighbor-aware Embedding for Node Clustering in Attributed Graphs"
date: 2021-08-05
publishDate: 2021-08-05T12:15:49.436331Z
authors: ["Chun Wang", "Shirui Pan", "Celina P Yu", "Ruiqi Hu", "Guodong Long", "Chengqi Zhang"]
publication_types: ["2"]
abstract: "Node clustering aims to partition the vertices in a graph into multiple groups or communities. Existing studies have mostly focused on developing deep learning approaches to learn a latent representation of nodes, based on which simple clustering methods like -means are applied. These two-step frameworks for node clustering are difficult to manipulate and usually lead to suboptimal performance, mainly because the graph embedding is not goal-directed, i.e., designed for the specific clustering task. In this paper, we propose a clustering-directed deep learning approach, Deep Neighbor-aware Embedded Node Clustering (DNENC for short) for clustering graph data. Our method focuses on attributed graphs to sufficiently explore the two sides of information in graphs. It encodes the topological structure and node content in a graph into a compact representation via a neighbor-aware graph autoencoder, which progressively absorbs information from neighbors via a convolutional or attentional encoder. Multiple neighbor-aware encoders are stacked to build a deep architecture followed by an inner-product decoder for reconstructing the graph structure. Furthermore, soft labels are generated to supervise a self-training process, which iteratively refines the node clustering results. The self-training process is jointly learned and optimized with the graph embedding in a unified framework, to benefit both components mutually. Experimental results compared with state-of-the-art algorithms demonstrate the good performance of our framework."
featured: false
publication: "Pattern Recognition"
tags: [ "Graph Neural Networks"]
url_pdf: ""
---
