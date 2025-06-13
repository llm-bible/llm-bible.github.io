---
layout: publication
title: 'Packdit: Joint Human Motion And Text Generation Via Mutual Prompting'
authors: Zhongyu Jiang, Wenhao Chai, Zhuoran Zhou, Cheng-yen Yang, Hsiang-wei Huang, Jenq-neng Hwang
conference: "Arxiv"
year: 2025
bibkey: jiang2025joint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.16551"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'GPT', 'Merging', 'Pretraining Methods', 'Transformer', 'Prompting', 'Applications']
---
Human motion generation has advanced markedly with the advent of diffusion
models. Most recent studies have concentrated on generating motion sequences
based on text prompts, commonly referred to as text-to-motion generation.
However, the bidirectional generation of motion and text, enabling tasks such
as motion-to-text alongside text-to-motion, has been largely unexplored. This
capability is essential for aligning diverse modalities and supports
unconditional generation. In this paper, we introduce PackDiT, the first
diffusion-based generative model capable of performing various tasks
simultaneously, including motion generation, motion prediction, text
generation, text-to-motion, motion-to-text, and joint motion-text generation.
Our core innovation leverages mutual blocks to integrate multiple diffusion
transformers (DiTs) across different modalities seamlessly. We train PackDiT on
the HumanML3D dataset, achieving state-of-the-art text-to-motion performance
with an FID score of 0.106, along with superior results in motion prediction
and in-between tasks. Our experiments further demonstrate that diffusion models
are effective for motion-to-text generation, achieving performance comparable
to that of autoregressive models.
