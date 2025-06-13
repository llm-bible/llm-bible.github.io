---
layout: publication
title: 'Infinitymath: A Scalable Instruction Tuning Dataset In Programmatic Mathematical Reasoning'
authors: Bo-wen Zhang, Yan Yan, Lin Li, Guang Liu
conference: "Arxiv"
year: 2024
bibkey: zhang2024scalable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.07089'}
  - {name: "Code", url: 'https://huggingface.co/datasets/flagopen/InfinityMATH'}
tags: ['Has Code', 'RAG', 'Security', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
Recent advancements in Chain-of-Thoughts (CoT) and Program-of-Thoughts (PoT)
methods have greatly enhanced language models' mathematical reasoning
capabilities, facilitating their integration into instruction tuning datasets
with LLMs. However, existing methods for large-scale dataset creation require
substantial seed data and high computational costs for data synthesis, posing
significant challenges for scalability. We introduce InfinityMATH, a scalable
instruction tuning dataset for programmatic mathematical reasoning. The
construction pipeline emphasizes decoupling numbers from mathematical problems
to synthesize number-independent programs, enabling efficient and flexible
scaling while minimizing dependency on specific numerical values. Fine-tuning
experiments with open-source language and code models, such as Llama2 and
CodeLlama, demonstrate the practical benefits of InfinityMATH. These fine-tuned
models, showed significant relative improvements on both in-domain and
out-of-domain benchmarks, ranging from 184.7% to 514.3% on average.
Additionally, these models exhibited high robustness on the GSM8K+ and MATH+
benchmarks, which are enhanced version of test sets with simply the number
variations. InfinityMATH ensures that models are more versatile and effective
across a broader range of mathematical problems. The data is available at
https://huggingface.co/datasets/flagopen/InfinityMATH.
