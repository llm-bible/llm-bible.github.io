---
layout: publication
title: 'Llava-more: A Comparative Study Of Llms And Visual Backbones For Enhanced Visual Instruction Tuning'
authors: Federico Cocchi, Nicholas Moratelli, Davide Caffagni, Sara Sarto, Lorenzo Baraldi, Marcella Cornia, Rita Cucchiara
conference: "Arxiv"
year: 2025
bibkey: cocchi2025llava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.15621"}
  - {name: "Code", url: "https://github.com/aimagelab/LLaVA-MORE"}
tags: ['Pre-Training', 'Tools', 'Survey Paper', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Multimodal Models']
---
Recent progress in Multimodal Large Language Models (MLLMs) has highlighted
the critical roles of both the visual backbone and the underlying language
model. While prior work has primarily focused on scaling these components to
billions of parameters, the trade-offs between model size, architecture, and
performance remain underexplored. Additionally, inconsistencies in training
data and evaluation protocols have hindered direct comparisons, making it
difficult to derive optimal design choices. In this paper, we introduce
LLaVA-MORE, a new family of MLLMs that integrates recent language models with
diverse visual backbones. To ensure fair comparisons, we employ a unified
training protocol applied consistently across all architectures. Our analysis
systematically explores both small- and medium-scale LLMs -- including Phi-4,
LLaMA-3.1, and Gemma-2 -- to evaluate multimodal reasoning, generation, and
instruction following, while examining the relationship between model size and
performance. Beyond evaluating the LLM impact on final results, we conduct a
comprehensive study of various visual encoders, ranging from CLIP-based
architectures to alternatives such as DINOv2, SigLIP, and SigLIP2. Additional
experiments investigate the effects of increased image resolution and
variations in pre-training datasets. Overall, our results provide insights into
the design of more effective MLLMs, offering a reproducible evaluation
framework that facilitates direct comparisons and can guide future model
development. Our source code and trained models are publicly available at:
https://github.com/aimagelab/LLaVA-MORE.
