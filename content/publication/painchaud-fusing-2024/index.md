---
title: Fusing Echocardiography Images and Medical Records for Continuous Patient Stratification
authors:
- Nathan Painchaud
- Pierre-Yves Courand
- Pierre-marc Jodoin
- Nicolas Duchateau
- Olivier Bernard
date: '2024-04-01'
publishDate: '2025-11-11T16:47:31.268772Z'
publication_types:
- paper-conference
abstract: Deep learning now enables automatic and robust extraction of cardiac function
  descriptors from echocardiographic sequences, such as ejection fraction or strain.
  These descriptors provide fine-grained information that physicians consider, in
  conjunction with global variables from the clinical record, to assess patients'
  condition. Drawing on novel transformer models applied to tabular data (e.g. variables
  from electronic health records), we propose a method that considers descriptors
  extracted from medical records and echocardiograms to learn a representation of
  hypertension, a difficult-to-characterize and highly prevalent cardiovascular pathology.
  Our method first embeds each descriptor separately using modality-specific approaches.
  These embeddings are fed as tokens to a transformer encoder, which combines them
  into a unified representation of the patient to predict a clinical rating. This
  task is formulated as an ordinal classification to enforce a pathological continuum
  in the representation space. We observe trends along this continuum for a cohort
  of 239 hypertensive patients to describe the gradual effects of hypertension on
  cardiac function descriptors. Our analysis shows that i) pretrained weights from
  a foundation model allow to reach good performance (83% accuracy) even with limited
  data ($textless$ 200 training samples), ii) trends across the population are reproducible
  between trainings, and iii) for descriptors known to interact with hypertension,
  patterns are consistent with prior physiological knowledge.
links:
- name: URL
  url: https://openreview.net/forum?id=atsESsgxPa
---
