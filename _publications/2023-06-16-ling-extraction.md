---
title: "Extraction of Volumetric Indices from Echocardiography: Which Deep Learning Solution for Clinical Use?"
collection: publications
permalink: /publication/2023-06-16-ling-extraction
type: proceedings
date: 2023-06-16
venue: 'Functional Imaging and Modeling of the Heart (FIMH)'
paperurl: 'https://doi.org/10.1007/978-3-031-35302-4_25'
citation: 'H. J. Ling, <b>N. Painchaud</b>, P.-Y. Courand, P.-M. Jodoin, D. Garcia, and O. Bernard, &quot;Extraction of Volumetric Indices from Echocardiography: Which Deep Learning Solution for Clinical Use?,&quot; in proc. <i>Functional Imaging and Modeling of the Heart (FIMH)</i>, 2023, pp. 245-254.'
---

Deep learning-based methods have spearheaded the automatic analysis of echocardiographic images, taking advantage of the publication of multiple open access datasets annotated by experts (CAMUS being one of the largest public databases). However, these models are still considered unreliable by clinicians due to unresolved issues concerning i) the temporal consistency of their predictions, and ii) their ability to generalize across datasets. In this context, we propose a comprehensive comparison between the current best performing methods in medical/echocardiographic image segmentation, with a particular focus on temporal consistency and cross-dataset aspects. We introduce a new private dataset, named CARDINAL, of apical two-chamber and apical four-chamber sequences, with reference segmentation over the full cardiac cycle. We show that the proposed 3D nnU-Net outperforms alternative 2D and recurrent segmentation methods. We also report that the best models trained on CARDINAL, when tested on CAMUS without any fine-tuning, still manage to perform competitively with respect to prior methods. Overall, the experimental results suggest that with sufficient training data, 3D nnU-Net could become the first automated tool to finally meet the standards of an everyday clinical device.