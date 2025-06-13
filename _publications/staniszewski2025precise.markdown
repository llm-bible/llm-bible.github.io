---
layout: publication
title: 'Precise Parameter Localization For Textual Generation In Diffusion Models'
authors: Łukasz Staniszewski, Bartosz Cywiński, Franziska Boenisch, Kamil Deja, Adam Dziedzic
conference: "Arxiv"
year: 2025
bibkey: staniszewski2025precise
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.09935'}
  - {name: "Code", url: 'https://t2i-text-loc.github.io/'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Merging', 'Pretraining Methods']
---
Novel diffusion models can synthesize photo-realistic images with integrated
high-quality text. Surprisingly, we demonstrate through attention activation
patching that only less than 1% of diffusion models' parameters, all contained
in attention layers, influence the generation of textual content within the
images. Building on this observation, we improve textual generation efficiency
and performance by targeting cross and joint attention layers of diffusion
models. We introduce several applications that benefit from localizing the
layers responsible for textual content generation. We first show that a
LoRA-based fine-tuning solely of the localized layers enhances, even more, the
general text-generation capabilities of large diffusion models while preserving
the quality and diversity of the diffusion models' generations. Then, we
demonstrate how we can use the localized layers to edit textual content in
generated images. Finally, we extend this idea to the practical use case of
preventing the generation of toxic text in a cost-free manner. In contrast to
prior work, our localization approach is broadly applicable across various
diffusion model architectures, including U-Net (e.g., LDM and SDXL) and
transformer-based (e.g., DeepFloyd IF and Stable Diffusion 3), utilizing
diverse text encoders (e.g., from CLIP to the large language models like T5).
Project page available at https://t2i-text-loc.github.io/.
