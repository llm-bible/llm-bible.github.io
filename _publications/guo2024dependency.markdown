---
layout: publication
title: Dependency-aware Semi-structured Sparsity: Declining Roles Of Outliers In Pruning Glu-based Llms
authors: Guo Zhiyu, Kamigaito Hidetaka, Wanatnabe Taro
conference: "Arxiv"
year: 2024
bibkey: guo2024dependency
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01943"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pruning', 'Quantization', 'RAG', 'Tools']
---
The rapid growth in the scale of Large Language Models (LLMs) has led to significant computational and memory costs making model compression techniques such as network pruning increasingly crucial for their efficient deployment. Recent LLMs such as LLaMA2 and Mistral have adopted GLU-based MLP architectures. However current LLM pruning strategies are primarily based on insights from older LLM architectures necessitating a reevaluation of these strategies to suit the new architectural characteristics. Contrary to traditional beliefs we find that outliers play a diminished role in the input projections of GLU-based MLPs. Leveraging this new insight we propose Dependency-aware Semi-structured Sparsity (DaSS) a novel pruning method for GLU-based LLMs. DaSS balances the flexibility of unstructured pruning and the structural consistency of dependency-based structured pruning by considering both of weight magnitude and corresponding intermediate activation norms in weight pruning metric. Empirical evaluations on the Mistral Gemma and LLaMA2 model families demonstrate the consistent effectiveness of DaSS in the prevailing GLU variants.
