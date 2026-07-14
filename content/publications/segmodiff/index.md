---
title: 'SegMoDiff: Semantic-Faithful Text-to-Motion Generation via Segmented Raw-Sequence Diffusion'

# Authors
# `me` is replaced with the full name from `data/authors/me.yaml` and linked to the profile.
authors:
  - me

date: '2026-07-01T00:00:00Z'
publishDate: '2026-07-01T00:00:00Z'

# Publication type from the CSL standard.
publication_types: ['paper-conference']

publication:
  name: "Proceedings of the 34th ACM International Conference on Multimedia (ACM MM)"
  short_name: "ACM MM"

peer_reviewed: true

abstract: Diffusion models have shown remarkable success in generating 3D human motion from text descriptions. However, existing approaches typically compress motion into a latent space, which sacrifices fine-grained semantic alignment between the text and the generated motion. We propose SegMoDiff, a text-to-motion diffusion framework that enables adequate and fine-grained semantic modeling directly on raw sequences by partitioning them into tractable segments. SegMoDiff pivots on a segmented motion diffusion transformer (SegMoDiT), where overlapping contextual attention is introduced to preserve cross-segment continuity while keeping the computational cost tractable. To make sampling practical, we further incorporate distribution matching distillation to reduce the number of sampling steps.

summary: A text-to-motion diffusion framework that models semantics directly on raw motion sequences by partitioning them into segments, with overlapping contextual attention and distribution matching distillation for fast sampling.

tags:
  - Diffusion Models
  - Human Motion Generation

# Display this page in the Featured widget?
featured: true

# Custom links
links: []

# Featured image
image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ""
---
