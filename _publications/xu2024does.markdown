---
layout: publication
title: 'Does Few-shot Learning Help LLM Performance In Code Synthesis?'
authors: Derek Xu, Tong Xie, Botao Xia, Haoyu Li, Yunsheng Bai, Yizhou Sun, Wei Wang
conference: "Arxiv"
year: 2024
bibkey: xu2024does
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.02906'}
tags: ['Interpretability and Explainability', 'Few-Shot', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Prompting']
---
Large language models (LLMs) have made significant strides at code generation
through improved model design, training, and chain-of-thought. However,
prompt-level optimizations remain an important yet under-explored aspect of
LLMs for coding. This work focuses on the few-shot examples present in most
code generation prompts, offering a systematic study on whether few-shot
examples improve LLM's coding capabilities, which few-shot examples have the
largest impact, and how to select impactful examples. Our work offers 2
approaches for selecting few-shot examples, a model-free method,
CODEEXEMPLAR-FREE, and a model-based method, CODEEXEMPLAR-BASED. The 2 methods
offer a trade-off between improved performance and reliance on training data
and interpretability. Both methods significantly improve CodeLlama's coding
ability across the popular HumanEval+ coding benchmark. In summary, our work
provides valuable insights into how to pick few-shot examples in code
generation prompts to improve LLM code generation capabilities.
