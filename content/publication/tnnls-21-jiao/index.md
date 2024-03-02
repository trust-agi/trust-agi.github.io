---
title: "Temporal Network Embedding for Link Prediction via VAE joint Attention Mechanism"
date: 2021-05-24
publishDate: 2021-05-24T12:19:12.824998Z
authors: ["Peifei Jiao", "Xuan Guo", "Xin Jing", "Dongxiao He", "Huaming Wu", "Shirui Pan", "Maoguo Gong", "Wenjun Wang"]
publication_types: ["2"]
abstract: "Network representation learning or embedding aims to project the network into a low-dimensional space that can be devoted to different network tasks, such as node classification, community detection, link prediction, and visualization. Temporal networks are an important type of networks whose topological structure changes over time. Compared with methods on static networks, temporal network embedding methods are facing three challenges: 1) it cannot describe the temporal dependency across network snapshots, 2) the node embedding in the latent space fails to indicate changes in the network topology and 3) it cannot avoid a lot of redundant computation via parameter inheritance on a series of snapshots. To overcome these problems, we propose a novel temporal network embedding method named TVAE, which is based on the Variational Auto-Encoder (VAE) to capture the evolution of temporal networks for link prediction. It not only generates low-dimensional embedding vectors of nodes, but also preserves the dynamic non-linear features of temporal networks. Through the combination of a self-attention mechanism and recurrent neural network, the proposed TVAE can update node representations while keeping the temporal dependency of vectors over time. We utilize parameter inheritance to keep the new embedding close to the previous one, rather than explicitly using regularization, thus it is effective for large-scale networks. We evaluate our model and several baselines on synthetic datasets and real-world networks. The experimental results demonstrate that TVAE has significant performance advantages and lower time cost compared with the baselines."
featured: false
publication: "IEEE Transactions on Neural Networks and Learning Systems (TNNLS)"
tags: ["Graph Neural Networks"]
url_pdf: ""
---
