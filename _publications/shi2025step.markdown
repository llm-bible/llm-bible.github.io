---
layout: publication
title: 'Swimvg: Step-wise Multimodal Fusion And Adaption For Visual Grounding'
authors: Liangtao Shi, Ting Liu, Xiantao Hu, Yue Hu, Quanjun Yin, Richang Hong
conference: "Arxiv"
year: 2025
bibkey: shi2025step
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16786"}
  - {name: "Code", url: "https://github.com/liuting20/SwimVG"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'Efficiency and Optimization', 'Model Architecture', 'Merging', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Visual grounding aims to ground an image region through natural language,
which heavily relies on cross-modal alignment. Most existing methods transfer
visual/linguistic knowledge separately by fully fine-tuning uni-modal
pre-trained models, followed by a simple stack of visual-language transformers
for multimodal fusion. However, these approaches not only limit adequate
interaction between visual and linguistic contexts, but also incur significant
computational costs. Therefore, to address these issues, we explore a step-wise
multimodal fusion and adaption framework, namely SwimVG. Specifically, SwimVG
proposes step-wise multimodal prompts (Swip) and cross-modal interactive
adapters (CIA) for visual grounding, replacing the cumbersome transformer
stacks for multimodal fusion. Swip can improve \{the\} alignment between the
vision and language representations step by step, in a token-level fusion
manner. In addition, weight-level CIA further promotes multimodal fusion by
cross-modal interaction. Swip and CIA are both parameter-efficient paradigms,
and they fuse the cross-modal features from shallow to deep layers gradually.
Experimental results on four widely-used benchmarks demonstrate that SwimVG
achieves remarkable abilities and considerable benefits in terms of efficiency.
Our code is available at https://github.com/liuting20/SwimVG.
