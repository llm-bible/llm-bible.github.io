---
layout: publication
title: 'Reconstructive Visual Instruction Tuning'
authors: Haochen Wang, Anlin Zheng, Yucheng Zhao, Tiancai Wang, Zheng Ge, Xiangyu Zhang, Zhaoxiang Zhang
conference: "Arxiv"
year: 2024
bibkey: wang2024reconstructive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09575"}
tags: ['RAG', 'Tools', 'Multimodal Models', 'Prompting']
---
This paper introduces reconstructive visual instruction tuning (ROSS), a
family of Large Multimodal Models (LMMs) that exploit vision-centric
supervision signals. In contrast to conventional visual instruction tuning
approaches that exclusively supervise text outputs, ROSS prompts LMMs to
supervise visual outputs via reconstructing input images. By doing so, it
capitalizes on the inherent richness and detail present within input images
themselves, which are often lost in pure text supervision. However, producing
meaningful feedback from natural images is challenging due to the heavy spatial
redundancy of visual signals. To address this issue, ROSS employs a denoising
objective to reconstruct latent representations of input images, avoiding
directly regressing exact raw RGB values. This intrinsic activation design
inherently encourages LMMs to maintain image detail, thereby enhancing their
fine-grained comprehension capabilities and reducing hallucinations.
Empirically, ROSS consistently brings significant improvements across different
visual encoders and language models. In comparison with extrinsic assistance
state-of-the-art alternatives that aggregate multiple visual experts, ROSS
delivers competitive performance with a single SigLIP visual encoder,
demonstrating the efficacy of our vision-centric supervision tailored for
visual outputs.
