---
title: 'Learning Stochastic Bridges for Video Object Removal via Video-to-Video Translation'

# Authors
# `me` is replaced with the full name from `data/authors/me.yaml` and linked to the profile.
authors:
  - Zijie Lou
  - Xiangwei Feng
  - me
  - Jiangtao Yao
  - Fei Che
  - Tianbao Liu
  - Chengjing Wu
  - Xiaochao Qu
  - Luoqi Liu
  - Ting Liu

date: '2026-04-01T00:00:00Z'
publishDate: '2026-04-01T00:00:00Z'

# Publication type from the CSL standard.
publication_types: ['paper-conference']

publication:
  name: "Proceedings of the 43rd International Conference on Machine Learning (ICML)"
  short_name: "ICML"

peer_reviewed: true

abstract: Existing video object removal methods predominantly rely on diffusion models following a noise-to-data paradigm, which starts from pure noise and is therefore poorly matched to a task whose input and output share most of their content. We instead reformulate video object removal as a video-to-video translation task via a stochastic bridge model, which directly transports the masked video to the clean video. To better exploit the mask signal, we propose a novel adaptive mask modulation strategy that lets the model perceive target regions across denoising steps.

summary: Reformulates video object removal as video-to-video translation with a stochastic bridge model instead of the noise-to-data diffusion paradigm, plus an adaptive mask modulation strategy.

tags:
  - Diffusion Models
  - Video Generation & Editing

# Display this page in the Featured widget?
featured: true

# Custom links
links:
  - type: source
    url: https://bridgeremoval.github.io/

# Featured image
image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ""
---
