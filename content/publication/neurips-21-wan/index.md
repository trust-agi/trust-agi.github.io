---
title: "Contrastive Graph Poisson Networks: Semi-Supervised Learning with Extremely Limited Labels"
date: 2021-09-28
publishDate: 2021-09-28T12:15:49.436331Z
authors: ["Sheng Wan", "Yibing Zhan", "Liu Liu", "Baosheng Yu", "Shirui Pan", "Chen Gong"]
publication_types: ["1"]
abstract: "Graph Neural Networks (GNNs) have achieved remarkable performance in the task of semi-supervised node classification. However, most existing GNN models require sufficient labeled data for effective network training. Their performance can be seriously degraded when labels are extremely limited. To address this issue, we propose a new framework termed Contrastive Graph Poisson Networks (CGPN) for node classification under extremely limited labeled data. Specifically, our CGPN derives from variational inference; integrates a newly designed Graph Poisson Network (GPN) to effectively propagate the limited labels to the entire graph and a normal GNN, such as Graph Attention Network, that flexibly guides the propagation of GPN; applies a contrastive objective to further exploit the supervision information from the learning process of GPN and GNN models. Essentially, our CGPN can enhance the learning performance of GNNs under extremely limited labels by contrastively propagating the limited labels to the entire graph. We conducted extensive experiments to demonstrate the superiority of CGPN. Specifically, when given only one label per category, our method significantly outperforms the second best competitors by 9.2%, 23.5%, and 6.7% on Cora, CiteSeer, and PubMed datasets, respectively. Codes are provided in the supplemental materials and will be released on GitHub."
featured: false
publication: "*2021 Conference on Neural Information Processing Systems, NeurIPS-21, Virtual-only Conference, 6-14, December, 2021*"
tags: ["Contrastive Learning", "Graph Neural Networks"]
url_pdf: ""
---