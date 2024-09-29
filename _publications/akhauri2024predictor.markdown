---
layout: publication
title: Shadowllm Predictor45;based Contextual Sparsity For Large Language Models
authors: Akhauri Yash, Abouelhamayed Ahmed F, Dotzel Jordan, Zhang Zhiru, Rush Alexander M, Huda Safeen, Abdelfattah Mohamed S
conference: "Arxiv"
year: 2024
bibkey: akhauri2024predictor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16635"}
  - {name: "Code", url: "https://github.com/abdelfattah&#45;lab/shadow&#95;llm/&#125;&#123;ShadowLLM&#125;"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pruning', 'Quantization', 'Tools']
---
The high power consumption and latency45;sensitive deployments of large language models (LLMs) have motivated techniques like quantization and sparsity. Contextual sparsity where the sparsity pattern is input45;dependent is crucial in LLMs because the permanent removal of attention heads or neurons from LLMs can significantly degrade accuracy. Prior work has attempted to model contextual sparsity using neural networks trained to predict activation magnitudes which can be used to dynamically prune structures with low predicted activation magnitude. In this paper we look beyond magnitude45;based pruning criteria to assess attention head and neuron importance in LLMs. We developed a novel predictor called ShadowLLM which can shadow the LLM behavior and enforce better sparsity patterns resulting in over 1537; improvement in end45;to45;end accuracy without increasing latency compared to previous methods. ShadowLLM achieves up to a 2037; speed45;up over the state45;of45;the45;art DejaVu framework. These enhancements are validated on models with up to 30 billion parameters. Our code is available at href123;https://github.com/abdelfattah&#45;lab/shadow&#95;llm/&#125;&#123;ShadowLLM&#125;.
