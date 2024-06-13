---
layout: post
title: Machine Learning and Data Science
date: 2022-04-20 10:14:00-0400
description: We studied the general area of machine learning and data science. A machine learning-based algorithm to is proposed to classify customer reviews. A variant of GAN, WGAN-GP, is designed to extend data set of EEG signals.
tags: Machine-Learning
# categories: GAN
giscus_comments: true
related_posts: false
toc:
  sidebar: left
---

## GAN-based EEG Signal Generation

_Abstract:_ Processing and analysis of brain signals generally requires a large amount of data. But the acquisition of 
EEG signals is difficult while the sample size of the data set is small, and sometimes categories are unbalanced in the 
data set. Based on the challenge, we proposed the WGAN-GP method, a variant of GAN, to generate useful EEG signals. 
The experiments on single-channel and multi-channel model both show that the performance of WGAN-GP is stable, and the 
generated signals have close shape with the real signals, and have better spectrum performance than traditional methods. 
Our results and analysis show that WGAN-GP can generate accurate and diverse EEG signals, and thus, help extend the data 
set which is difficult to collect physically. We’ve made the code associated with this work available 
at https://github.com/warrenzha/GAN-EEG-generation.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/posts/generatedeeg.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/posts/wganconverge.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Generated EEG signals and convergence rate of WGAN-GP.
</div>

[PDF](https://warrenzha.github.io/assets/pdf/GAN-EEG-Generation.pdf)

[Link](https://github.com/warrenzha/GAN-EEG-generation)      

## Classification of Online Customer Reviews

_Abstract:_ Customer reviews on e-commerce platforms contain valuable information, while sifting through them manually 
tends to dismay people because of the huge amount of data. This study implemented a machine learning-based algorithm to 
classify customer reviews. Our classifier extracts Chinese word segmentation and text frequency for feature extraction 
and scoring, and implements the classification with methods of Naive Bayesian and Support Vector Machines. Experimental 
results on the Taobao product review sentiment datasets show that our model based on two machine learning algorithms, 
though results in different performances, can provide suggestions on the selection of the identification classifier 
using a trade-off strategy and helps obtain fast and accurate classification on reviews of different categories.

[PDF](https://iopscience.iop.org/article/10.1088/1742-6596/1678/1/012081/pdf)

