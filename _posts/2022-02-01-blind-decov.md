---
layout: post
title: Blind Deconvolution Using Convex Programming
date: 2022-02-01 10:14:00-0400
description: Implementation of blind deconvolution using convex programming.
tags: Optimization
# categories: optimization
giscus_comments: true
related_posts: false
toc:
  sidebar: left
---

_Abstract:_ We study the question of recovering two signals w and x from their convolution y = w ∗ x. Generally, the solution to this blind deconvolution problem is non-unique and non-convex. But with assumptions on sparsity, subspace structure and transformed variable, we can convert the non-convex nuclear norm into a convex problem by ”dual-dual” relaxation. In this project, we also implement the convex algorithm proposed in Blind Deconvolution Using Convex Programming, and compare its performance with non-blind and non-convex algorithms. Moreover, the evaluation shows that the convex algorithm is robust against sparsity violation, but sensitive to low-rank condition. At last, we try to extend the algorithm to 2D deconvolution by recovering a blurred image. But the result on 2D deconvolution still need improvement.

[Link](https://github.com/warrenzha/blind-deconvolution)