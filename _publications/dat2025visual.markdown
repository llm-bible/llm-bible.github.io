---
layout: publication
title: 'VSC: Visual Search Compositional Text-to-image Diffusion Model'
authors: Do Huu Dat, Nam Hyeonu, Po-yuan Mao, Tae-hyun Oh
conference: "Arxiv"
year: 2025
bibkey: dat2025visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01104"}
tags: ['Fine-Tuning', 'RAG', 'Model Architecture', 'Merging', 'Security', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting']
---
Text-to-image diffusion models have shown impressive capabilities in
generating realistic visuals from natural-language prompts, yet they often
struggle with accurately binding attributes to corresponding objects,
especially in prompts containing multiple attribute-object pairs. This
challenge primarily arises from the limitations of commonly used text encoders,
such as CLIP, which can fail to encode complex linguistic relationships and
modifiers effectively. Existing approaches have attempted to mitigate these
issues through attention map control during inference and the use of layout
information or fine-tuning during training, yet they face performance drops
with increased prompt complexity. In this work, we introduce a novel
compositional generation method that leverages pairwise image embeddings to
improve attribute-object binding. Our approach decomposes complex prompts into
sub-prompts, generates corresponding images, and computes visual prototypes
that fuse with text embeddings to enhance representation. By applying
segmentation-based localization training, we address cross-attention
misalignment, achieving improved accuracy in binding multiple attributes to
objects. Our approaches outperform existing compositional text-to-image
diffusion models on the benchmark T2I CompBench, achieving better image
quality, evaluated by humans, and emerging robustness under scaling number of
binding pairs in the prompt.
