---
layout: publication
title: 'Generative AI Beyond Llms: System Implications Of Multi-modal Generation'
authors: Alicia Golden, Samuel Hsia, Fei Sun, Bilge Acun, Basil Hosmer, Yejin Lee, Zachary Devito, Jeff Johnson, Gu-yeon Wei, David Brooks, Carole-jean Wu
conference: "Arxiv"
year: 2023
bibkey: golden2023generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.14385"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Attention Mechanism', 'Pretraining Methods']
---
As the development of large-scale Generative AI models evolve beyond text
(1D) generation to include image (2D) and video (3D) generation, processing
spatial and temporal information presents unique challenges to quality,
performance, and efficiency. We present the first work towards understanding
this new system design space for multi-modal text-to-image (TTI) and
text-to-video (TTV) generation models. Current model architecture designs are
bifurcated into 2 categories: Diffusion- and Transformer-based models. Our
systematic performance characterization on a suite of eight representative
TTI/TTV models shows that after state-of-the-art optimization techniques such
as Flash Attention are applied, Convolution accounts for up to 44% of execution
time for Diffusion-based TTI models, while Linear layers consume up to 49% of
execution time for Transformer-based models. We additionally observe that
Diffusion-based TTI models resemble the Prefill stage of LLM inference, and
benefit from 1.1-2.5x greater speedup from Flash Attention than
Transformer-based TTI models that resemble the Decode phase. Since
optimizations designed for LLMs do not map directly onto TTI/TTV models, we
must conduct a thorough characterization of these workloads to gain insights
for new optimization opportunities. In doing so, we define sequence length in
the context of TTI/TTV models and observe sequence length can vary up to 4x in
Diffusion model inference. We additionally observe temporal aspects of TTV
workloads pose unique system bottlenecks, with Temporal Attention accounting
for over 60% of total Attention time. Overall, our in-depth system performance
characterization is a critical first step towards designing efficient and
deployable systems for emerging TTI/TTV workloads.
