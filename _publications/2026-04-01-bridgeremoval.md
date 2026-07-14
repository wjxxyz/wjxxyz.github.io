---
title: "Learning Stochastic Bridges for Video Object Removal via Video-to-Video Translation"
collection: publications
category: conferences
permalink: /publication/2026-04-01-bridgeremoval
excerpt: 'We reformulate video object removal as a video-to-video translation task via an SDE-based stochastic bridge model, establishing a direct stochastic path from the source video to the target. It leverages input priors for better removal, introduces an adaptive mask modulation strategy, and outperforms existing methods in visual quality and temporal consistency.'
date: 2026-04-01
venue: 'International Conference on Machine Learning (ICML) 2026'
paperurl: 'https://bridgeremoval.github.io/'
citation: 'Zijie Lou*, Xiangwei Feng*, Jiaxin Wang, Jiangtao Yao, Fei Che, Tianbao Liu, Chengjing Wu, Xiaochao Qu, Luoqi Liu, Ting Liu. (2026). &quot;Learning Stochastic Bridges for Video Object Removal via Video-to-Video Translation.&quot; <i>International Conference on Machine Learning (ICML) 2026</i>. Accepted.'
---
*Jiaxin Wang (Second Author), ICML 2026 (Accepted)*

## Abstract

Existing video object removal methods predominantly rely on diffusion models following a noise-to-data paradigm, where generation starts from uninformative Gaussian noise. This approach discards the rich structural and contextual priors present in the original input video. Consequently, such methods often lack sufficient guidance, leading to incomplete object erasure or the synthesis of implausible content that conflicts with the scene's physical logic. In this paper, we reformulate video object removal as a video-to-video translation task via a stochastic bridge model. Unlike noise-initialized methods, our framework establishes a direct stochastic path from the source video (with objects) to the target video (objects removed). This bridge formulation effectively leverages the input video as a strong structural prior, guiding the model to perform precise removal while ensuring that the filled regions are logically consistent with the surrounding environment. To address the trade-off where strong bridge priors hinder the removal of large objects, we propose a novel adaptive mask modulation strategy. This mechanism dynamically modulates input embeddings based on mask characteristics, balancing background fidelity with generative flexibility. Extensive experiments demonstrate that our approach significantly outperforms existing methods in both visual quality and temporal consistency. The project page is [https://bridgeremoval.github.io/](https://bridgeremoval.github.io/).

## Contributions

- We propose **BridgeRemoval**, a novel video-to-video generative framework that utilizes an SDE-based bridge model to reformulate video object removal. By establishing a direct stochastic path from the source video to the target, our method effectively leverages input priors to achieve better object removal.
- We introduce an adaptive mask modulation strategy that dynamically balances the trade-off between background fidelity and generative flexibility, ensuring robust performance across objects of varying scales.
- To provide a comprehensive evaluation of video object removal models, we propose **BridgeRemoval-Bench**, which encompasses a wide variety of scenarios and provides meticulously annotated masks.
- Extensive experiments demonstrate the effectiveness of our approach in diverse real-world scenarios, outperforming existing methods in both visual quality and temporal coherence, while also highlighting the potential of our framework to be extended to other video editing tasks.

[Project Page](https://bridgeremoval.github.io/)
