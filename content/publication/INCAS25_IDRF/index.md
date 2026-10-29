---
title: 'Malicious QUIC C2 Traffic Detection based on Random Forest in Programmable Data Plane'

authors:
  - admin
  - Xiaoquan Zhang
  - Yi Bai
  - Lin Cui

date: '2025-01-01T00:00:00Z'
doi: 'https://doi.org/10.1145/3769699.3771588'

publication_types: ['paper-conference']
publication: ACM CoNEXT Workshop on In-Network Computing and AI for Distributed Systems
publication_short: INCAS '25 (EI)

pages: '21–27'

abstract: 'The widespread adoption of QUIC, an encrypted transport protocol, presents novel challenges for network security. Its underlying UDP-based connectionless design, full encryption, and multiplexed streams hinder traditional Deep Packet Inspection (DPI) and behavior-based detection methods. At the same time, Command-and-Control (C2) channels increasingly adopt QUIC to evade detection in advanced persistent threat (APT) attacks. This paper presents a real-time C2 detection framework built on programmable data planes and lightweight Random Forest classifiers. By embedding in-network telemetry (INT) metadata and compiling trained models into switch-executable rule tables, the proposed system enables near-source malicious flow detection at microsecond latency. We demonstrate the feasibility of deploying decision-tree-based inference within resource-constrained P4 switches, achieving 99.83% detection accuracy on server-based training and 82.1% on programmable hardware, with a 2–3 orders of magnitude reduction in inference latency. Our findings outline a novel design space for encrypted traffic inspection under performance and scalability constraints.'

tags:
  - QUIC Protocol
  - C2 Detection
  - Programmable Data Plane
  - Random Forest

featured: true

url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3769699.3771588'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ''
---
