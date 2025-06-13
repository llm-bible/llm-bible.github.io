---
layout: publication
title: 'Slim-llm: Salience-driven Mixed-precision Quantization For Large Language Models'
authors: Wei Huang, Haotong Qin, Yangdong Liu, Yawei Li, Qinshuo Liu, Xianglong Liu, Luca Benini, Michele Magno, Shiming Zhang, Xiaojuan Qi
conference: "Arxiv"
year: 2024
bibkey: huang2024slim
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14917"}
  - {name: "Code", url: "https://github.com/Aaronhuang-778/SliM-LLM"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Quantization', 'Has Code']
---
Post-training quantization (PTQ) is an effective technique for compressing large language models (LLMs). However, while uniform-precision quantization is computationally efficient, it often compromises model performance. To address this, we propose SliM-LLM, a salience-driven mixed-precision quantization framework that allocates bit-widths at the group-wise. Our approach leverages the observation that important weights follow a structured distribution and introduces two key components: \textbf\{1)\} \textit\{Salience-Determined Bit Allocation\} adaptively assigns bit-widths to groups within each layer based on their salience; and \textbf\{2)\} \textit\{Salience-Weighted Quantizer Calibration\} optimizes quantizer parameters by incorporating element-level salience. With its structured partitioning, SliM-LLM provides a hardware-friendly solution that matches the efficiency of uniform quantization methods while improving accuracy. Experiments show that SliM-LLM achieves superior performance across various LLMs at low bit-widths. For example, a 2-bit quantized LLaMA-7B model reduces memory usage by nearly 6x compared to the floating-point baseline, decreases perplexity by 48% compared to state-of-the-art gradient-free PTQ methods, and maintains GPU inference speed. Additionally, the extended version, SliM-LLM\\(^+\\), which incorporates gradient-based quantization, further reduces perplexity by 35.1%. Our code is available at https://github.com/Aaronhuang-778/SliM-LLM
