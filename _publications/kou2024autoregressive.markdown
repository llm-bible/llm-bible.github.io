---
layout: publication
title: 'Orthus: Autoregressive Interleaved Image-text Generation With Modality-specific Heads'
authors: Siqi Kou, Jiachun Jin, Zhihong Liu, Chang Liu, Ye Ma, Jian Jia, Quan Chen, Peng Jiang, Zhijie Deng
conference: "Arxiv"
year: 2024
bibkey: kou2024autoregressive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.00127'}
tags: ['Language Modeling', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'GPT', 'Quantization', 'Merging', 'Prompting', 'Multimodal Models', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
We introduce Orthus, an autoregressive (AR) transformer that excels in
generating images given textual prompts, answering questions based on visual
inputs, and even crafting lengthy image-text interleaved contents. Unlike prior
arts on unified multimodal modeling, Orthus simultaneously copes with discrete
text tokens and continuous image features under the AR modeling principle. The
continuous treatment of visual signals minimizes the information loss for both
image understanding and generation while the fully AR formulation renders the
characterization of the correlation between modalities straightforward. The key
mechanism enabling Orthus to leverage these advantages lies in its
modality-specific heads -- one regular language modeling (LM) head predicts
discrete text tokens and one diffusion head generates continuous image features
conditioning on the output of the backbone. We devise an efficient strategy for
building Orthus -- by substituting the Vector Quantization (VQ) operation in
the existing unified AR model with a soft alternative, introducing a diffusion
head, and tuning the added modules to reconstruct images, we can create an
Orthus-base model effortlessly (e.g., within mere 72 A100 GPU hours).
Orthus-base can further embrace post-training to better model interleaved
images and texts. Empirically, Orthus surpasses competing baselines including
Show-o and Chameleon across standard benchmarks, achieving a GenEval score of
0.58 and an MME-P score of 1265.8 using 7B parameters. Orthus also shows
exceptional mixed-modality generation capabilities, reflecting the potential
for handling intricate practical generation tasks.
