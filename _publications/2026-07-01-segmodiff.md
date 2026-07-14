---
title: "SegMoDiff: Semantic-Faithful Text-to-Motion Generation via Segmented Raw-Sequence Diffusion"
collection: publications
category: conferences
permalink: /publication/2026-07-01-segmodiff
excerpt: 'We propose SegMoDiff, a text-to-motion diffusion framework that operates directly on segmented raw sequences, enabling adequate and fine-grained semantic modeling. It introduces SegMoDiT with overlapping contextual attention, segment-wise text enhancement, and distribution matching distillation, outperforming state-of-the-art methods in semantic fidelity with faster inference.'
date: 2026-07-01
venue: 'ACM Multimedia (ACM MM) 2026'
citation: '王嘉欣 (First Author). (2026). &quot;SegMoDiff: Semantic-Faithful Text-to-Motion Generation via Segmented Raw-Sequence Diffusion.&quot; <i>ACM Multimedia (ACM MM) 2026</i>. Accepted.'
---
*王嘉欣 (First Author), ACM MM 2026 (Accepted)*

## Abstract

Diffusion models have shown remarkable success in generating 3D human motion from text descriptions, demonstrating superior realism and diversity. However, directly modeling the full raw motion sequence is computationally intractable. Existing diffusion-based methods either compromise essential computations on the raw sequence or perform low-dimensional modeling in a latent space, inevitably introducing semantic deviations. To overcome this challenge, we propose **SegMoDiff**, a text-to-motion diffusion framework that enables adequate and fine-grained semantic modeling directly on raw sequences by partitioning them into tractable segments. SegMoDiff pivots on a segmented motion diffusion transformer (**SegMoDiT**), where overlapping contextual attention is introduced to preserve cross-segment coherence. On top of this, segment-wise text enhancement based on large language models is leveraged to achieve precise text-motion alignment. To further accelerate inference speed, we incorporate distribution matching distillation to reduce sampling steps. Extensive experiments demonstrate that our method significantly outperforms state-of-the-art methods in semantic fidelity while delivering superior inference speed.

## Contributions

- We propose **SegMoDiff**, a text-to-motion diffusion framework that operates directly on segmented raw sequences. Extensive experiments show that it outperforms state-of-the-art methods in semantic fidelity with faster inference.
- We design **SegMoDiT** with overlapping contextual attention (OCA), which effectively reduces the computational cost of full raw-sequence modeling while preserving cross-segment coherence for generation.
- We introduce segment-wise text enhancement, and further incorporate DMD into the segmented diffusion to yield a more efficient variant of SegMoDiff with precise text-motion alignment.
