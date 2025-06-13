---
layout: publication
title: 'Dyst-xl: Dynamic Layout Planning And Content Control For Compositional Text-to-video Generation'
authors: Weijie He, Mushui Liu, Yunlong Yu, Zhao Wang, Chao Wu
conference: "Arxiv"
year: 2025
bibkey: he2025dyst
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15032"}
  - {name: "Code", url: "https://github.com/XiaoBuL/DyST-XL"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Merging', 'Transformer', 'Has Code', 'Prompting', 'Attention Mechanism']
---
Compositional text-to-video generation, which requires synthesizing dynamic
scenes with multiple interacting entities and precise spatial-temporal
relationships, remains a critical challenge for diffusion-based models.
Existing methods struggle with layout discontinuity, entity identity drift, and
implausible interaction dynamics due to unconstrained cross-attention
mechanisms and inadequate physics-aware reasoning. To address these
limitations, we propose DyST-XL, a \textbf\{training-free\} framework that
enhances off-the-shelf text-to-video models (e.g., CogVideoX-5B) through
frame-aware control. DyST-XL integrates three key innovations: (1) A Dynamic
Layout Planner that leverages large language models (LLMs) to parse input
prompts into entity-attribute graphs and generates physics-aware keyframe
layouts, with intermediate frames interpolated via trajectory optimization; (2)
A Dual-Prompt Controlled Attention Mechanism that enforces localized text-video
alignment through frame-aware attention masking, achieving precise control over
individual entities; and (3) An Entity-Consistency Constraint strategy that
propagates first-frame feature embeddings to subsequent frames during
denoising, preserving object identity without manual annotation. Experiments
demonstrate that DyST-XL excels in compositional text-to-video generation,
significantly improving performance on complex prompts and bridging a crucial
gap in training-free video synthesis. The code is released in
https://github.com/XiaoBuL/DyST-XL.
