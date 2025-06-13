---
layout: publication
title: 'FP4 All The Way: Fully Quantized Training Of Llms'
authors: Brian Chmiel, Maxim Fishman, Ron Banner, Daniel Soudry
conference: "Arxiv"
year: 2025
bibkey: chmiel2025all
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19115"}
  - {name: "Code", url: "https://github.com/Anonymous1252022/fp4-all-the-way"}
tags: ['Efficiency and Optimization', 'RAG', 'Training Techniques', 'Has Code', 'Quantization']
---
We demonstrate, for the first time, fully quantized training (FQT) of large language models (LLMs) using predominantly 4-bit floating-point (FP4) precision for weights, activations, and gradients on datasets up to 200 billion tokens. We extensively investigate key design choices for FP4, including block sizes, scaling formats, and rounding methods. Our analysis shows that the NVFP4 format, where each block of 16 FP4 values (E2M1) shares a scale represented in E4M3, provides optimal results. We use stochastic rounding for backward and update passes and round-to-nearest for the forward pass to enhance stability. Additionally, we identify a theoretical and empirical threshold for effective quantized training: when the gradient norm falls below approximately \\(\sqrt\{3\}\\) times the quantization noise, quantized training becomes less effective. Leveraging these insights, we successfully train a 7-billion-parameter model on 256 Intel Gaudi2 accelerators. The resulting FP4-trained model achieves downstream task performance comparable to a standard BF16 baseline, confirming that FP4 training is a practical and highly efficient approach for large-scale LLM training. A reference implementation is supplied in https://github.com/Anonymous1252022/fp4-all-the-way .
