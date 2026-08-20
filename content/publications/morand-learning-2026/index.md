---
title: "Learning to Reconnect: Graph-based Path Classification for Restoring Retinal Vessel Segmentation Connectivity"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Oscar Morand
- admin
- Jonathan Fabrizio
- Odyssée Merveille
- Elodie Puybareau

date: '2026-08-14'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-workshop"]

# Publication name and optional abbreviated publication name.
publication: "accepted for *Shape in Medical Imaging (ShapeMI) @ Medical Image Computing and Computer Assisted Intervention (MICCAI)*"
publication_short: "accepted for *ShapeMI @ MICCAI*"

abstract: "Accurate segmentation of retinal blood vessels in 2D fundus images is
  essential for reconstructing complete vascular trees and enabling downstream
  analyses that require a reliable vascular topology. However, most deep
  learning approaches rely on pixel-wise segmentation, which can lead to vessel
  discontinuities, particularly in thin or low-contrast regions. These
  fragmentation errors can affect the structural integrity of the reconstructed
  vascular network and impact subsequent modeling tasks. Tracking-based methods
  and automated post-processing approaches have been proposed to reconnect
  fragmented segments, but they often rely on accurately identifying beforehand
  which points to reconnect along the vascular skeleton. In practice,
  determining which endpoints should be connected remains a challenging problem
  and typically requires manual intervention. To address this limitation, we
  introduce an automated framework designed to identify vessel point pairs that
  should be reconnected. Instead of relying on handcrafted geometric criteria,
  we formulate reconnection as a path classification problem: given a candidate
  path between two vessel points in a binary mask, the model determines whether
  a direct vessel segment exists between them. By encoding complete paths as
  single entities, our approach leverages image information along the entire
  potential connection. Experimental results on retinal images from the FIVES
  dataset show that our approach effectively identifies disconnected segments
  in predicted vascular masks, substantially outperforming geometric baselines
  and providing a reliable guidance for downstream reconnection methods. Code
  is publicly available at https://github.com/oscarmorand/EVAPORE/tree/shapeMI."

# Summary. An optional shortened abstract.
summary: "We formulate reconnection as a path classification problem: given a candidate path between two vessel points in a binary mask, the model determines whether a direct vessel segment exists between them."

tags:
- Vascular connectivity # 1st tag is displayed for featured publication, so override alphabetical order to display the most relevant tag
- Path-level classification
- Retinal fundus imaging
- Segmentation post-processing

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 
links:
- name: OpenReview
  url: https://openreview.net/forum?id=VMB7oinVjk
- type: code
  url: https://github.com/oscarmorand/EVAPORE/tree/shapeMI
---
