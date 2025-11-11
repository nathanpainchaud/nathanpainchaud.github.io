---
title: Fusing Echocardiography Images and Medical Records for Continuous Patient Stratification
authors:
- Nathan Painchaud
- Jérémie Stym-Popper
- Pierre-Yves Courand
- Nicolas Thome
- Pierre-Marc Jodoin
- Nicolas Duchateau
- Olivier Bernard
date: '2025-10-01'
publishDate: '2025-11-11T16:47:31.259308Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Ultrasonics, Ferroelectrics, and Frequency Control*'
doi: 10.1109/TUFFC.2025.3600902
abstract: 'Deep learning enables automatic and robust extraction of cardiac function
  descriptors from echocardiographic sequences, such as ejection fraction (EF) or
  strain. These descriptors provide fine-grained information that physicians consider,
  in conjunction with more global variables from the clinical record, to assess patients’
  condition. Drawing on novel Transformer models applied to tabular data, we propose
  a method that considers all descriptors extracted from medical records and echocardiograms
  to learn the representation of a cardiovascular pathology with a difficult-to-characterize
  continuum, namely hypertension. Our method first projects each variable into its
  own representation space using modality-specific approaches. These standardized
  representations of multimodal data are then fed to a Transformer encoder, which
  learns to merge them into a comprehensive representation of the patient through
  the task of predicting a clinical rating. This stratification task is formulated
  as an ordinal classification to enforce a pathological continuum in the representation
  space. We observe the major trends along this continuum on a cohort of 239 hypertensive
  patients, providing unprecedented details in the description of hypertension’s impact
  on various cardiac function descriptors. Our analysis shows that: 1) the XTab foundation
  model’s architecture allows to reach high performance (96.8% AUROC) even with limited
  data (less than 200 training samples); 2) stratification across the population is
  reproducible between trainings [within 5.7% of mean absolute error (MAE)]; and 3)
  patterns emerge in descriptors, some of which align with established physiological
  knowledge about hypertension, while others could pave the way for a more comprehensive
  understanding of this pathology. The code is available at https://github.com/creatis-myriad/didactic'
tags:
- Deep learning
- Training
- Hypertension
- Transformers
- Feature extraction
- representation learning
- Data models
- Data mining
- Pathology
- Medical services
- Adaptation models
- Cardiac ultrasound
- health records
- hypertension
- multimodal
- stratification
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/11131320
---
