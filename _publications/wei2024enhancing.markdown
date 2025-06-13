---
layout: publication
title: 'Enhancing Mmdit-based Text-to-image Models For Similar Subject Generation'
authors: Tianyi Wei, Dongdong Chen, Yifan Zhou, Xingang Pan
conference: "Arxiv"
year: 2024
bibkey: wei2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18301"}
  - {name: "Code", url: "https://github.com/wtybest/EnMMDiT"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Merging', 'Pretraining Methods', 'Transformer', 'Has Code', 'Prompting']
---
Representing the cutting-edge technique of text-to-image models, the latest
Multimodal Diffusion Transformer (MMDiT) largely mitigates many generation
issues existing in previous models. However, we discover that it still suffers
from subject neglect or mixing when the input text prompt contains multiple
subjects of similar semantics or appearance. We identify three possible
ambiguities within the MMDiT architecture that cause this problem: Inter-block
Ambiguity, Text Encoder Ambiguity, and Semantic Ambiguity. To address these
issues, we propose to repair the ambiguous latent on-the-fly by test-time
optimization at early denoising steps. In detail, we design three loss
functions: Block Alignment Loss, Text Encoder Alignment Loss, and Overlap Loss,
each tailored to mitigate these ambiguities. Despite significant improvements,
we observe that semantic ambiguity persists when generating multiple similar
subjects, as the guidance provided by overlap loss is not explicit enough.
Therefore, we further propose Overlap Online Detection and Back-to-Start
Sampling Strategy to alleviate the problem. Experimental results on a newly
constructed challenging dataset of similar subjects validate the effectiveness
of our approach, showing superior generation quality and much higher success
rates over existing methods. Our code will be available at
https://github.com/wtybest/EnMMDiT.
