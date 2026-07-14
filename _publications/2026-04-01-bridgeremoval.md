---
title: "Learning Stochastic Bridges for Video Object Removal via Video-to-Video Translation"
collection: publications
category: conferences
permalink: /publication/2026-04-01-bridgeremoval
excerpt: '将视频目标消除重新建模为基于随机桥（stochastic bridge）的视频到视频翻译任务 BridgeRemoval，建立从源视频到目标视频的直接随机路径，充分利用输入视频的结构先验；提出自适应掩码调制策略平衡背景保真与生成灵活性，在视觉质量与时序一致性上显著优于现有方法。'
date: 2026-04-01
venue: 'International Conference on Machine Learning (ICML) 2026'
paperurl: 'https://bridgeremoval.github.io/'
citation: 'Zijie Lou*, Xiangwei Feng*, Jiaxin Wang, Jiangtao Yao, Fei Che, Tianbao Liu, Chengjing Wu, Xiaochao Qu, Luoqi Liu, Ting Liu. (2026). &quot;Learning Stochastic Bridges for Video Object Removal via Video-to-Video Translation.&quot; <i>International Conference on Machine Learning (ICML) 2026</i>. 已录用.'
---
（第二作者，ICML 2026 已录用）

## Abstract

Existing video object removal methods predominantly rely on diffusion models following a noise-to-data paradigm, where generation starts from uninformative Gaussian noise. This approach discards the rich structural and contextual priors present in the original input video. Consequently, such methods often lack sufficient guidance, leading to incomplete object erasure or the synthesis of implausible content that conflicts with the scene's physical logic. In this paper, we reformulate video object removal as a video-to-video translation task via a stochastic bridge model. Unlike noise-initialized methods, our framework establishes a direct stochastic path from the source video (with objects) to the target video (objects removed). This bridge formulation effectively leverages the input video as a strong structural prior, guiding the model to perform precise removal while ensuring that the filled regions are logically consistent with the surrounding environment. To address the trade-off where strong bridge priors hinder the removal of large objects, we propose a novel adaptive mask modulation strategy. This mechanism dynamically modulates input embeddings based on mask characteristics, balancing background fidelity with generative flexibility. Extensive experiments demonstrate that our approach significantly outperforms existing methods in both visual quality and temporal consistency. The project page is [https://bridgeremoval.github.io/](https://bridgeremoval.github.io/).

## Contributions

- 提出 **BridgeRemoval**——一个基于 SDE 随机桥模型的视频到视频生成框架，将视频目标消除重新建模为从源视频到目标视频的直接随机路径，有效利用输入先验实现更优的目标移除。
- 引入自适应掩码调制（adaptive mask modulation）策略，根据掩码特性动态平衡背景保真度与生成灵活性，在不同尺度目标上均保持稳健性能。
- 构建 **BridgeRemoval-Bench** 评测基准，涵盖多样化场景并提供精细标注掩码，用于全面评估视频目标消除模型。
- 大量实验证明该方法在多样真实场景下的有效性，在视觉质量与时序连贯性上均超越现有方法，并展现出扩展到其他视频编辑任务的潜力。

[项目主页](https://bridgeremoval.github.io/)
