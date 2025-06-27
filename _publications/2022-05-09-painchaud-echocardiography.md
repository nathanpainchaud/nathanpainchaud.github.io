---
title: "Echocardiography Segmentation With Enforced Temporal Consistency"
collection: publications
category: manuscripts
permalink: /publication/2022-05-09-painchaud-echocardiography
excerpt: 'In this paper, we propose a framework to learn the 2D+time apical long-axis cardiac shape such that the segmented sequences can benefit from temporal and anatomical consistency constraints.'
date: 2022-05-09
venue: 'IEEE Transactions on Medical Imaging (IEEE TMI)'
slidesurl: '/files/painchaud_echocardiography_2022_slides.pdf'
paperurl: 'https://doi.org/10.1109/TMI.2022.3173669'
bibtexurl: '/files/painchaud_cardiac_2020.bib'
citation: '<b>N. Painchaud</b>, N. Duchateau, O. Bernard, and P.-M. Jodoin, &quot;Echocardiography Segmentation With Enforced Temporal Consistency,&quot; <i>IEEE Transactions on Medical Imaging</i>, vol. 41, no. 10, pp. 2867–2878, Oct. 2022.'
---

Convolutional neural networks (CNN) have demonstrated their ability to segment 2D cardiac ultrasound images. However, despite recent successes according to which the intra-observer variability on end-diastole and end-systole images has been reached, CNNs still struggle to leverage temporal information to provide accurate and temporally consistent segmentation maps across the whole cycle. Such consistency is required to accurately describe the cardiac function, a necessary step in diagnosing many cardiovascular diseases. In this paper, we propose a framework to learn the 2D+time apical long-axis cardiac shape such that the segmented sequences can benefit from temporal and anatomical consistency constraints. Our method is a post-processing that takes as input segmented echocardiographic sequences produced by any state-of-the-art method and processes it in two steps to (i) identify spatio-temporal inconsistencies according to the overall dynamics of the cardiac sequence and (ii) correct the inconsistencies. The identification and correction of cardiac inconsistencies relies on a constrained autoencoder trained to learn a physiologically interpretable embedding of cardiac shapes, where we can both detect and fix anomalies. We tested our framework on 98 full-cycle sequences from the CAMUS dataset, which are available alongside this paper. Our temporal regularization method not only improves the accuracy of the segmentation across the whole sequences, but also enforces temporal and anatomical consistency.