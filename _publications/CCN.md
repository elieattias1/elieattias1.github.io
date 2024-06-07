---
title: "Pixel-Based Similarities as Alternative to Neural Data in CNN Regularization Against Adversarial Attacks"
collection: publications
permalink: /publication/CCN
excerpt: 'This paper is about a neuroscience inspired defense against adversarial attacks.'
date: 2024-08-06
venue: 'Cognitive Computational Neuroscience'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://elieattias1.github.io/files/CCN.pdf'
citation: 'Elie Attias, Cengiz Pehlevan, Dina Obeid (2024)'
---

Convolutional Neural Networks (CNNs) excel in many visual
tasks but are highly sensitive to slight input perturbations that
are imperceptible to the human eye, often resulting in task
failures. Recent studies indicate that training CNNs with reg-
ularizers that promote brain-like representations, using neural
recordings, can improve model robustness. However, the re-
quirement to collect neural data restricts the utility of these
methods. Is it possible to develop regularizers that mimic
the computational function of neural regularizers without the
need for direct neural recordings, thereby expanding the us-
ability and effectiveness of these techniques? In this work,
we inspect a neural regularizer introduced in Li et al. (2019)
to extract its underlying strength. This regularizer uses neural
representational similarities, which we find also correlate with
pixel similarities. Motivated by this finding, we introduce a new
regularizer that retains the essence of the original but is com-
puted using only image pixel similarities, eliminating the need
for neural recordings. We show that our regularizer signifi-
cantly advances model robustness for a wide range of black
box attacks. Our work opens the door to explore how biologi-
cally motivated loss functions can be used to drive the perfor-
mance of artificial neural networks using a method accessible
to the broader machine learning community