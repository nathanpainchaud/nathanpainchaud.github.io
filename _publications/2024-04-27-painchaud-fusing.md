---
title: "Fusing Echocardiography Images and Medical Records for Continuous Patient Stratification"
collection: publications
category: conferences
permalink: /publication/2024-04-27-painchaud-fusing
excerpt: 'Drawing on novel transformer models applied to tabular data (e.g. variables from electronic health records), we propose a method that considers descriptors extracted from medical records and echocardiograms to learn a representation of hypertension.'
date: 2024-04-27
venue: 'Medical Imaging with Deep Learning (MIDL)'
paperurl: 'https://openreview.net/forum?id=atsESsgxPa'
bibtexurl: '/files/painchaud_fusing_2024.bib'
citation: '<b>N. Painchaud</b>, P.-Y. Courand, P.-M. Jodoin, N. Duchateau, and O. Bernard, &quot;Fusing Echocardiography Images and Medical Records for Continuous Patient Stratification,&quot; presented at <i>Medical Imaging with Deep Learning (MIDL)</i>, 2024.'
---

Deep learning now enables automatic and robust extraction of cardiac function descriptors from echocardiographic sequences, such as ejection fraction or strain. These descriptors provide fine-grained information that physicians consider, in conjunction with global variables from the clinical record, to assess patients' condition. Drawing on novel transformer models applied to tabular data (e.g. variables from electronic health records), we propose a method that considers descriptors extracted from medical records and echocardiograms to learn a representation of hypertension, a difficult-to-characterize and highly prevalent cardiovascular pathology. Our method first embeds each descriptor separately using modality-specific approaches. These embeddings are fed as tokens to a transformer encoder, which combines them into a unified representation of the patient to predict a clinical rating. This task is formulated as an ordinal classification to enforce a pathological continuum in the representation space. We observe trends along this continuum for a cohort of 239 hypertensive patients to describe the gradual effects of hypertension on cardiac function descriptors. Our analysis shows that i) pretrained weights from a foundation model allow to reach good performance (83% accuracy) even with limited data (<200 training samples), ii) trends across the population are reproducible between trainings, and iii) for descriptors known to interact with hypertension, patterns are consistent with prior physiological knowledge.