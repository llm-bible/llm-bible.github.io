---
layout: publication
title: 'Consistyle: Style Diversity In Training-free Consistent T2I Generation'
authors: Yohai Mazuz, Janna Bruner, Lior Wolf
conference: "Arxiv"
year: 2025
bibkey: mazuz2025style
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20626"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting']
---
In text-to-image models, consistent character generation is the task of achieving text alignment while maintaining the subject's appearance across different prompts. However, since style and appearance are often entangled, the existing methods struggle to preserve consistent subject characteristics while adhering to varying style prompts. Current approaches for consistent text-to-image generation typically rely on large-scale fine-tuning on curated image sets or per-subject optimization, which either fail to generalize across prompts or do not align well with textual descriptions. Meanwhile, training-free methods often fail to maintain subject consistency across different styles. In this work, we introduce a training-free method that achieves both style alignment and subject consistency. The attention matrices are manipulated such that Queries and Keys are obtained from the anchor image(s) that are used to define the subject, while the Values are imported from a parallel copy that is not subject-anchored. Additionally, cross-image components are added to the self-attention mechanism by expanding the Key and Value matrices. To do without shifting from the target style, we align the statistics of the Value matrices. As is demonstrated in a comprehensive battery of qualitative and quantitative experiments, our method effectively decouples style from subject appearance and enables faithful generation of text-aligned images with consistent characters across diverse styles.
