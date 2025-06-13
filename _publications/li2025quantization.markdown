---
layout: publication
title: 'Quantization Meets Reasoning: Exploring LLM Low-bit Quantization Degradation For Mathematical Reasoning'
authors: Zhen Li, Yupeng Su, Runming Yang, Congkai Xie, Zheng Wang, Zhongwei Xie, Ngai Wong, Hongxia Yang
conference: "Arxiv"
year: 2025
bibkey: li2025quantization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.03035"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Quantization', 'Pretraining Methods', 'Fine-Tuning']
---
Large language models have achieved significant advancements in complex
mathematical reasoning benchmarks, such as MATH. However, their substantial
computational requirements present challenges for practical deployment. Model
quantization has emerged as an effective strategy to reduce memory usage and
computational costs by employing lower precision and bit-width representations.
In this study, we systematically evaluate the impact of quantization on
mathematical reasoning tasks. Our results demonstrate that aggressive
quantization methods like AWQ and GPTQ introduce up to 32.39% accuracy
degradation (average 11.31%) on Llama-3 models, particularly in numerical
computation and reasoning planning. To address this, we introduce a
multidimensional evaluation framework combining qualitative capability analysis
and quantitative error assessment. We further develop targeted recovery
strategies, showing that fine-tuning quantized models on only 545 task-specific
examples for 3 minutes on 4 GPUs effectively restores reasoning capabilities to
near full-precision levels. Additionally, our error assessment pipeline
achieves 98.9% accuracy in diagnosing and localizing errors across 3,366
failure cases, providing actionable insights for mitigating
quantization-induced degradation.
