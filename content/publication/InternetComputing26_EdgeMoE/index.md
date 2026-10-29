---
title: 'EdgeMoE: Collaborative Mixture-of-Experts Inference for Programmable Edge Networks'

authors:
    - admin
    - Bowen Liang
    - Xiaoquan Zhang
    - Fung Po Tso
    - Weijia Jia
    - Lin Cui

date: '2026-10-27T00:00:00Z'
doi: 'https://doi.org/10.1109/MIC.2026.3746361'

publication_types: ['article-journal']
publication: IEEE Internet Computing
publication_short: IEEE Internet Computing (SCI-Q2)

tags:
  - Edge Computing
  - Mixture of Experts
  - In-network Inference
  - Programmable Data Plane

abstract: Edge networks increasingly require real-time traffic intelligence to support latency-sensitive tasks such as traffic classification, intrusion detection, and anomaly monitoring. However, deploying expressive machine learning models in programmable data planes remains challenging under strict switch resource constraints. This article presents EdgeMoE, a dataplane-compatible mixture-of-experts (MoE) inference framework that enables collaborative expert execution across multiple programmable edge devices. Rather than concentrating inference within a single switch, EdgeMoE distributes specialized expert models and coordinates them through a lightweight gating mechanism deployed within the data plane. A hardware resource-aware optimization and knowledge distillation pipeline produces compact gating and expert models. Prototype results on Intel Tofino switches show that EdgeMoE achieves the highest mean Macro-F1 and exceeds the strongest baseline on each task by 0.63~7.70 percentage points, with a deployable per-switch hardware footprint and nanosecond-level inference latency.

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11755456'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Display this page in the Featured widget?
featured: true
image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ''
---
