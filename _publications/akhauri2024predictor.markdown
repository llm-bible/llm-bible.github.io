---
layout: publication
title: 'Shadowllm: Predictor-based Contextual Sparsity For Large Language Models'
authors: Yash Akhauri, Ahmed F Abouelhamayed, Jordan Dotzel, Zhiru Zhang, Alexander M Rush, Safeen Huda, Mohamed S Abdelfattah
conference: "Arxiv"
year: 2024
bibkey: akhauri2024predictor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16635"}
  - {name: "Code", url: "https://github.com/abdelfattah-lab/shadow_llm/}{ShadowLLM"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Pruning', 'Quantization', 'Has Code', 'Applications', 'Attention Mechanism']
---
The high power consumption and latency-sensitive deployments of large
language models (LLMs) have motivated efficiency techniques like quantization
and sparsity. Contextual sparsity, where the sparsity pattern is
input-dependent, is crucial in LLMs because the permanent removal of attention
heads or neurons from LLMs can significantly degrade accuracy. Prior work has
attempted to model contextual sparsity using neural networks trained to predict
activation magnitudes, which can be used to dynamically prune structures with
low predicted activation magnitude. In this paper, we look beyond
magnitude-based pruning criteria to assess attention head and neuron importance
in LLMs. We develop a novel predictor called ShadowLLM, which can shadow the
LLM behavior and enforce better sparsity patterns, resulting in over 15%
improvement in end-to-end accuracy compared to prior methods. In addition,
ShadowLLM achieves up to a 20% speed-up over the state-of-the-art DejaVu
framework. These enhancements are validated on Llama-2 and OPT models with up
to 30 billion parameters. Our code is available at
\href\{https://github.com/abdelfattah-lab/shadow_llm/\}\{ShadowLLM\}.
