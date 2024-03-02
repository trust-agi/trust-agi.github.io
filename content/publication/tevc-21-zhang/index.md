---
title: "Convolutional Neural Networks based Lung Nodule Classification: A Surrogate-Assisted Evolutionary Algorithm for Hyperparameter Optimization"
date: 2021-02-15
publishDate: 2020-02-15T12:19:12.824998Z
authors: ["Miao Zhang", "Huiqi Li", "Shirui Pan", "Juan Lyu", "Steve Ling", "Steven Su"]
publication_types: ["2"]
abstract: "This paper investigates deep neural networks (DNNs) based lung nodule classification with hyperparameter optimization. Hyperparameter optimization in DNNs is a computationally expensive problem, and a surrogate-assisted evolutionary algorithm has been recently introduced to automatically search for optimal hyperparameter configurations of DNNs, by applying computationally efficient surrogate models to approximate the validation error function of hyperparameter configurations. Different from existing surrogate models adopting stationary covariance functions (kernels) to measure the difference between hyperparameter points, this paper proposes a non-stationary kernel that allows the surrogate model to adapt to functions whose smoothness varies with the spatial location of inputs. A multi-level convolutional neural network (ML-CNN) is built for lung nodule classification, and the hyperparameter configuration is optimized by the proposed non-stationary kernel-based Gaussian surrogate model. Our algorithm searches with a surrogate for optimal setting via a hyperparameter importance based evolutionary strategy, and the experiments demonstrate our algorithm outperforms manual tuning and several well-established hyperparameter optimization methods, including random search, grid Search, the Tree-structured Parzen Estimator Approach (TPE), Gaussian processes (GP) with stationary kernels, and the recently proposed Hyperparameter Optimization via RBF and Dynamic coordinate search (HORD)."
featured: false
publication: "*IEEE Transactions on Evolutionary Computation, TEvC*"
tags: ["Deep Learning"]
---
