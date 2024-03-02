---
title: "One-Shot Neural Architecture Search: Maximising Diversity to Overcome
Catastrophic Forgetting"
date: 2020-10-27
publishDate: 2020-10-27T12:19:12.824998Z
authors: ["Miao Zhang", "Huiqi Li", "Shirui Pan", "Xiaojun Chang", "Chuan Zhou", "Zongyuan Ge", "Steven Su"]
publication_types: ["2"]
abstract: "One-shot neural architecture search (NAS) has recently become mainstream in the NAS community because it significantly improves computational efficiency through weight sharing. However, the supernet training paradigm in one-shot NAS introduces catastrophic forgetting, where each step of the training can deteriorate the performance of other architectures that contain partially-shared weights with current architecture. To overcome this problem of catastrophic forgetting, we formulate supernet training for one-shot NAS as a constrained continual learning optimization problem such that learning the current architecture does not degrade the validation accuracy of previous architectures. The key to solving this constrained optimization problem is a novelty search based architecture selection (NSAS) loss function that regularizes the supernet training by using a greedy novelty search method to find the most representative subset. We applied the NSAS loss function to two one-shot NAS baselines and extensively tested them on both a common search space and a NAS benchmark dataset. We further derive three variants based on the NSAS loss function, the NSAS with depth constrain (NSAS-C) to improve  the transferability, and NSAS-G and NSAS-LG to handle the situation with a limited number of constraints. The experiments on the common NAS search space demonstrate that NSAS and it variants improve the predictive ability of supernet training in one-shot NAS with remarkable and efficient performance on the CIFAR-10, CIFAR-100, and ImageNet datasets. The results with the NAS benchmark dataset also confirm the significant improvements these one-shot NAS baselines can make"
featured: false
publication: "*IEEE Transactions on Pattern Analysis and Machine Intelligence, TPAMI*"
tags: ["Neural Architecture Search"]
---
