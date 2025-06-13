---
layout: publication
title: 'RILQ: Rank-insensitive Lora-based Quantization Error Compensation For Boosting 2-bit Large Language Model Accuracy'
authors: Geonho Lee, Janghwan Lee, Sukjin Hong, Minsoo Kim, Euijai Ahn, Du-seong Chang, Jungwook Choi
conference: "Arxiv"
year: 2024
bibkey: lee2024rank
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.01129'}
  - {name: "Code", url: 'https://github.com/aiha-lab/RILQ'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Merging', 'Quantization', 'Fine-Tuning', 'Pretraining Methods']
---
Low-rank adaptation (LoRA) has become the dominant method for
parameter-efficient LLM fine-tuning, with LoRA-based quantization error
compensation (LQEC) emerging as a powerful tool for recovering accuracy in
compressed LLMs. However, LQEC has underperformed in sub-4-bit scenarios, with
no prior investigation into understanding this limitation. We propose RILQ
(Rank-Insensitive LoRA-based Quantization Error Compensation) to understand
fundamental limitation and boost 2-bit LLM accuracy. Based on rank analysis
revealing model-wise activation discrepancy loss's rank-insensitive nature,
RILQ employs this loss to adjust adapters cooperatively across layers, enabling
robust error compensation with low-rank adapters. Evaluations on LLaMA-2 and
LLaMA-3 demonstrate RILQ's consistent improvements in 2-bit quantized inference
across various state-of-the-art quantizers and enhanced accuracy in
task-specific fine-tuning. RILQ maintains computational efficiency comparable
to existing LoRA methods, enabling adapter-merged weight-quantized LLM
inference with significantly enhanced accuracy, making it a promising approach
for boosting 2-bit LLM performance. Our code is available at
https://github.com/aiha-lab/RILQ.
