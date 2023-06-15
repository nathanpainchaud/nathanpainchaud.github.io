---
title: "On the effectiveness of GAN generated cardiac MRIs for segmentation"
collection: publications
permalink: /publication/2020-01-25-skandarani-effectiveness
date: 2020-01-25
venue: 'Medical Imaging with Deep Learning (MIDL)'
paperurl: 'https://openreview.net/forum?id=f9Pl3Qj3_Q'
citation: 'Y. Skandarani, <b>N. Painchaud</b>, P.-M. Jodoin, and A. Lalande, &quot;On the effectiveness of GAN generated cardiac MRIs for segmentation,&quot; presented at <i>Medical Imaging with Deep Learning (MIDL)</i>, 2020.'
---

In this work, we propose a Variational Autoencoder (VAE) - Generative Adversarial Networks (GAN) model that can produce highly realistic MRI together with its pixel accurate groundtruth for the application of cine-MR image cardiac segmentation.  On one side of our model is a Variational Autoencoder (VAE) trained to learn the latent representations of cardiac shapes.  On the other side is a GAN that uses  ”SPatially-Adaptive (DE)Normalization” (SPADE) modules to generate realistic MR images tailored to a given anatomical map.  At test time, the sampling of the VAE latent space allows to generate an arbitrary large number of cardiac shapes, which are fed to the GAN that subsequently generates MR images whose cardiac structure fits that of the cardiac shapes.  In other words, our system can generate a large volume of realistic yet labeled cardiac MR images.  We show that segmentation with CNNs trained with our synthetic annotated images gets competitive results compared to traditional techniques.
We also show that combining data augmentation with our GAN-generated images lead to an improvement in the Dice score of up to 12 percent while allowing for better generalization capabilities on  other datasets.