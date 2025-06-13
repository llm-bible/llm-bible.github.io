---
layout: publication
title: 'Visual Adaptive Prompting For Compositional Zero-shot Learning'
authors: Kyle Stein, Arash Mahyari, Guillermo Francia, Eman El-sheikh
conference: "Arxiv"
year: 2025
bibkey: stein2025visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20292"}
tags: ['Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models', 'Prompting']
---
Vision-Language Models (VLMs) have demonstrated impressive capabilities in
learning joint representations of visual and textual data, making them powerful
tools for tasks such as Compositional Zero-Shot Learning (CZSL). CZSL requires
models to generalize to novel combinations of visual primitives-such as
attributes and objects-that were not explicitly encountered during training.
Recent works in prompting for CZSL have focused on modifying inputs for the
text encoder, often using static prompts that do not change across varying
visual contexts. However, these approaches struggle to fully capture varying
visual contexts, as they focus on text adaptation rather than leveraging visual
features for compositional reasoning. To address this, we propose Visual
Adaptive Prompting System (VAPS) that leverages a learnable visual prompt
repository and similarity-based retrieval mechanism within the framework of
VLMs to bridge the gap between semantic and visual features. Our method
introduces a dynamic visual prompt repository mechanism that selects the most
relevant attribute and object prompts based on the visual features of the
image. Our proposed system includes a visual prompt adapter that encourages the
model to learn a more generalizable embedding space. Experiments on three CZSL
benchmarks, across both closed and open-world scenarios, demonstrate
state-of-the-art results.
