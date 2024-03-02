---
title: "Medical Code Assignment with Gated Convolution and Note-Code Interaction"
date: 2021-05-06
publishDate: 2021-05-06T13:36:24.239997Z
authors: ["Shaoxiong Ji", "Shirui Pan", "Pekka Marttinen"]
publication_types: ["1"]
abstract: "Medical code assignment from clinical text is a fundamental task in clinical information system management. As medical notes are typically lengthy and the medical coding system's code space is large, this task is a long-standing challenge. Recent work applies deep neural network models to encode the medical notes and assign medical codes to clinical documents. However, these methods are still ineffective as they do not fully encode and capture the lengthy and rich semantic information of medical notes nor explicitly exploit the interactions between the notes and codes. We propose a novel method, gated convolutional neural networks, and a note-code interaction (GatedCNN-NCI), for automatic medical code assignment to overcome these challenges. Our methods capture the rich semantic information of the lengthy clinical text for better representation by utilizing embedding injection and gated information propagation in the medical note encoding module. With a novel note-code interaction design and a graph message passing mechanism, we explicitly capture the underlying dependency between notes and codes, enabling effective code prediction. A weight sharing scheme is further designed to decrease the number of trainable parameters. Empirical experiments on real-world clinical datasets show that our proposed model outperforms state-of-the-art models in most cases, and our model size is on par with light-weighted baselines. ."
featured: false
publication: "*Findings of ACL: ACL-2021*"
tags: ["Medical Code Assignment"]
url_pdf: "https://arxiv.org/pdf/2010.06975.pdf"
---
