---
title: Cardiac MRI Segmentation with Strong Anatomical Guarantees
authors:
- Nathan Painchaud
- Youssef Skandarani
- Thierry Judge
- Olivier Bernard
- Alain Lalande
- Pierre-Marc Jodoin
date: '2019-01-01'
publishDate: '2025-11-11T16:47:31.217602Z'
publication_types:
- paper-conference
publication: '*Medical Image Computing and Computer Assisted Intervention – MICCAI
  2019*'
doi: 10.1007/978-3-030-32245-8_70
abstract: Recent publications have shown that the segmentation accuracy of modern-day
  convolutional neural networks (CNN) applied on cardiac MRI can reach the inter-expert
  variability, a great achievement in this area of research. However, despite these
  successes, CNNs still produce anatomically inaccurate segmentations as they provide
  no guarantee on the anatomical plausibility of their outcome, even when using a
  shape prior. In this paper, we propose a cardiac MRI segmentation method which always
  produces anatomically plausible results. At the core of the method is an adversarial
  variational autoencoder (aVAE) whose latent space encodes a smooth manifold on which
  lies a large spectrum of valid cardiac shapes. This aVAE is used to automatically
  warp anatomically inaccurate cardiac shapes towards a close but correct shape. Our
  method can accommodate any cardiac segmentation method and convert its anatomically
  implausible results to plausible ones without affecting its overall geometric and
  clinical metrics. With our method, CNNs can now produce results that are both within
  the inter-expert variability and always anatomically plausible.
tags:
- Cardiac MRI segmentation
- CNN
- Variational autoencoder
---
