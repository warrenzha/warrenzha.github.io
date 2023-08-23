---
layout: page
title: Information Science
description: Signal processing and learning method for information science.
img: assets/img/eeg_signals.jpeg
importance: 2
category: research
---

GAN-based EEG Signal Generation
------
Abstract: Processing and analysis of brain signals generally requires a large amount of data. But the acquisition of EEG signals is difficult while the sample size of the data set is small, and sometimes categories are unbalanced in the data set. Based on the challenge, we proposed the WGAN-GP method, a variant of GAN, to generate useful EEG signals. The experiments on single-channel and multi-channel model both show that the performance of WGAN-GP is stable, and the generated signals have close shape with the real signals, and have better spectrum performance than traditional methods. Our results and analysis show that WGAN-GP can generate accurate and diverse EEG signals, and thus, help extend the data set which is difficult to collect physically. We’ve made the code associated with this work available at https://github.com/wyzhao030/WGAN-GP.

Blind Deconvolution Using Convex Programming
------
Abstract: We study the question of recovering two signals w and x from their convolution y = w ∗ x. Generally, the solution to this blind deconvolution problem is non-unique and non-convex. But with assumptions on sparsity, subspace structure and transformed variable, we can convert the non-convex nuclear norm into a convex problem by ”dual-dual” relaxation. In this project, we also implement the convex algorithm proposed in Blind Deconvolution Using Convex Programming, and compare its performance with non-blind and non-convex algorithms. Moreover, the evaluation shows that the convex algorithm is robust against sparsity violation, but sensitive to low-rank condition. At last, we try to extend the algorithm to 2D deconvolution by recovering a blurred image. But the result on 2D deconvolution still need improvement.

ML-based Customer Review Classification
------
Abstract: Customer reviews on e-commerce platforms contain valuable information, while sifting through them manually tends to dismay people because of the huge amount of data. This study implemented a machine learning-based algorithm to classify customer reviews. Our classifier extracts Chinese word segmentation and text frequency for feature extraction and scoring, and implements the classification with methods of Naive Bayesian and Support Vector Machines. Experimental results on the Taobao product review sentiment datasets show that our model based on two machine learning algorithms, though results in different performances, can provide suggestions on the selection of the identification classifier using a trade-off strategy and helps obtain fast and accurate classification on reviews of different categories.