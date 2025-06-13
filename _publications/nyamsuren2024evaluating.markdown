---
layout: publication
title: 'Evaluating Quantized Large Language Models For Code Generation On Low-resource Language Benchmarks'
authors: Enkhbold Nyamsuren
conference: "Arxiv"
year: 2024
bibkey: nyamsuren2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14766"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'RAG', 'GPT', 'Quantization', 'Ethics and Bias', 'Applications']
---
Democratization of AI is an important topic within the broader topic of the
digital divide. This issue is relevant to LLMs, which are becoming popular as
AI co-pilots but suffer from a lack of accessibility due to high computational
demand. In this study, we evaluate whether quantization is a viable approach
toward enabling LLMs on generic consumer devices. The study assesses the
performance of five quantized code LLMs in Lua code generation tasks. To
evaluate the impact of quantization, the models with 7B parameters were tested
on a consumer laptop at 2-, 4-, and 8-bit integer precisions and compared to
non-quantized code LLMs with 1.3, 2, and 3 billion parameters. Lua is chosen as
a low-level resource language to avoid models' biases related to high-resource
languages. The results suggest that the models quantized at the 4-bit integer
precision offer the best trade-off between performance and model size. These
models can be comfortably deployed on an average laptop without a dedicated
GPU. The performance significantly drops at the 2-bit integer precision. The
models at 8-bit integer precision require more inference time that does not
effectively translate to better performance. The 4-bit models with 7 billion
parameters also considerably outperform non-quantized models with lower
parameter numbers despite having comparable model sizes with respect to storage
and memory demand. While quantization indeed increases the accessibility of
smaller LLMs with 7 billion parameters, these LLMs demonstrate overall low
performance (less than 50%) on high-precision and low-resource tasks such as
Lua code generation. While accessibility is improved, usability is still not at
the practical level comparable to foundational LLMs such as GPT-4o or Llama 3.1
405B.
