---
title: "A Brain-Inspired Regularizer for Adversarial Robustness"
collection: publications
permalink: /publication/arxiv
excerpt: 'This paper presents further results of the paper cited below.'
date: 2024-10-08
# venue: 'Cognitive Computational Neuroscience Conference'
# slidesurl: 'http://elieattias1.github.io/files/CCN_Poster.pdf'
paperurl: 'https://arxiv.org/abs/2410.03952'
citation: 'Elie Attias, Cengiz Pehlevan, Dina Obeid (2024)'
---

Convolutional Neural Networks (CNNs) excel in many visual tasks, but they tend to be sensitive to slight input perturbations that are imperceptible to the human eye, often resulting in task failures. Recent studies indicate that training CNNs with regularizers that promote brain-like representations, using neural recordings, can improve model robustness. However, the requirement to use neural data severely restricts the utility of these methods. Is it possible to develop regularizers that mimic the computational function of neural regularizers without the need for neural recordings, thereby expanding the usability and effectiveness of these techniques? In this work, we inspect a neural regularizer introduced in Li et al. (2019) to extract its underlying strength. The regularizer uses neural representational similarities, which we find also correlate with pixel similarities. Motivated by this finding, we introduce a new regularizer that retains the essence of the original but is computed using image pixel similarities, eliminating the need for neural recordings.  We show that our regularization method 1) significantly increases model robustness to a range of black box attacks on various datasets and 2) is computationally inexpensive and relies only on original datasets. Our work explores how biologically motivated loss functions can be used to drive the performance of artificial neural networks.
