---
title: "Cardiac MRI Segmentation with Strong Anatomical Guarantees"
collection: publications
category: conferences
permalink: /publication/2019-10-10-painchaud-cardiac
date: 2019-10-10
venue: 'Medical Image Computing and Computer Assisted Intervention (MICCAI)'
paperurl: 'https://doi.org/10.1007/978-3-030-32245-8_70'
citation: '<b>N. Painchaud</b>, Y. Skandarani, T. Judge, O. Bernard, A. Lalande, and P.-M. Jodoin, &quot;Cardiac MRI Segmentation with Strong Anatomical Guarantees,&quot; in proc. <i>Medical Image Computing and Computer Assisted Intervention (MICCAI)</i>, 2019, pp. 632–640.'
---

Recent publications have shown that the segmentation accuracy of modern-day convolutional neural networks (CNN) applied on cardiac MRI can reach the inter-expert variability, a great achievement in this area of research. However, despite these successes, CNNs still produce anatomically inaccurate segmentations as they provide no guarantee on the anatomical plausibility of their outcome, even when using a shape prior. In this paper, we propose a cardiac MRI segmentation method which always produces anatomically plausible results. At the core of the method is an adversarial variational autoencoder (aVAE) whose latent space encodes a smooth manifold on which lies a large spectrum of valid cardiac shapes. This aVAE is used to automatically warp anatomically inaccurate cardiac shapes towards a close but correct shape. Our method can accommodate any cardiac segmentation method and convert its anatomically implausible results to plausible ones without affecting its overall geometric and clinical metrics. With our method, CNNs can now produce results that are both within the inter-expert variability and always anatomically plausible.