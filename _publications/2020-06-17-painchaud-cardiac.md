---
title: "Cardiac Segmentation with Strong Anatomical Guarantees"
collection: publications
permalink: /publication/2020-06-17-painchaud-cardiac
type: journal
date: 2020-06-17
venue: 'IEEE Transactions on Medical Imaging (IEEE TMI)'
paperurl: 'https://doi.org/10.1109/TMI.2020.3003240'
citation: '<b>N. Painchaud</b>, Y. Skandarani, T. Judge, O. Bernard, A. Lalande, and P.-M. Jodoin, &quot;Cardiac Segmentation with Strong Anatomical Guarantees,&quot; <i>IEEE Transactions on Medical Imaging</i>, vol. 39, no. 11, pp. 3703–3713, Nov. 2020.'
---

Convolutional neural networks (CNN) have had unprecedented success in medical imaging and, in particular, in medical image segmentation. However, despite the fact that segmentation results are closer than ever to the inter-expert variability, CNNs are not immune to producing anatomically inaccurate segmentations, even when built upon a shape prior. In this paper, we present a framework for producing cardiac image segmentation maps that are guaranteed to respect pre-defined anatomical criteria, while remaining within the inter-expert variability. The idea behind our method is to use a well-trained CNN, have it process cardiac images, identify the anatomically implausible results and warp these results toward the closest anatomically valid cardiac shape. This warping procedure is carried out with a constrained variational autoencoder (cVAE) trained to learn a representation of valid cardiac shapes through a smooth, yet constrained, latent space. With this cVAE, we can project any implausible shape into the cardiac latent space and steer it toward the closest correct shape. We tested our framework on short-axis MRI as well as apical two and four-chamber view ultrasound images, two modalities for which cardiac shapes are drastically different. With our method, CNNs can now produce results that are both within the inter-expert variability and always anatomically plausible without having to rely on a shape prior.