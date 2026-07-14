---
title: "SegMoDiff: Semantic-Faithful Text-to-Motion Generation via Segmented Raw-Sequence Diffusion"
collection: publications
category: conferences
permalink: /publication/2026-07-01-segmodiff
excerpt: '提出面向文本引导的原始动作序列分段扩散框架 SegMoDiff，通过将原始序列切分为可处理的片段，直接在原始序列上实现充分且细粒度的语义建模；设计 SegMoDiT、重叠上下文注意力（OCA）与片段级文本增强，结合分布匹配蒸馏（DMD）在语义保真度与推理速度上均超越现有方法。'
date: 2026-07-01
venue: 'ACM Multimedia (ACM MM) 2026'
citation: '王嘉欣（第一作者）. (2026). &quot;SegMoDiff: Semantic-Faithful Text-to-Motion Generation via Segmented Raw-Sequence Diffusion.&quot; <i>ACM Multimedia (ACM MM) 2026</i>. 已录用.'
---
（第一作者，ACM MM 2026 已录用）

## Abstract

Diffusion models have shown remarkable success in generating 3D human motion from text descriptions, demonstrating superior realism and diversity. However, directly modeling the full raw motion sequence is computationally intractable. Existing diffusion-based methods either compromise essential computations on the raw sequence or perform low-dimensional modeling in a latent space, inevitably introducing semantic deviations. To overcome this challenge, we propose **SegMoDiff**, a text-to-motion diffusion framework that enables adequate and fine-grained semantic modeling directly on raw sequences by partitioning them into tractable segments. SegMoDiff pivots on a segmented motion diffusion transformer (**SegMoDiT**), where overlapping contextual attention is introduced to preserve cross-segment coherence. On top of this, segment-wise text enhancement based on large language models is leveraged to achieve precise text-motion alignment. To further accelerate inference speed, we incorporate distribution matching distillation to reduce sampling steps. Extensive experiments demonstrate that our method significantly outperforms state-of-the-art methods in semantic fidelity while delivering superior inference speed.

## Contributions

- 提出 **SegMoDiff**——一个直接在分段原始序列上运行的文本到动作扩散框架。大量实验表明，该方法在语义保真度上超越现有最优方法，同时具备更快的推理速度。
- 设计带有重叠上下文注意力（OCA）的 **SegMoDiT**，在有效降低完整原始序列建模计算开销的同时，保持跨片段生成的连贯性。
- 引入片段级文本增强（segment-wise text enhancement），并进一步将分布匹配蒸馏（DMD）融入分段扩散，得到推理更高效、且文本-动作对齐更精确的 SegMoDiff 变体。
