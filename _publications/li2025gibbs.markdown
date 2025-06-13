---
layout: publication
title: 'Gift: Gibbs Fine-tuning For Code Generation'
authors: Haochen Li, Wanjin Feng, Xin Zhou, Zhiqi Shen
conference: "Arxiv"
year: 2025
bibkey: li2025gibbs
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11466"}
  - {name: "Code", url: "https://github.com/Alex-HaochenLi/GiFT"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
Training Large Language Models (LLMs) with synthetic data is a prevalent practice in code generation. A key approach is self-training, where LLMs are iteratively trained on self-generated correct code snippets. In this case, the self-generated codes are drawn from a conditional distribution, conditioned on a specific seed description. However, the seed description is not the only valid representation that aligns with its intended meaning. With all valid descriptions and codes forming a joint space, codes drawn from the conditional distribution would lead to an underrepresentation of the full description-code space. As such, we propose Gibbs Fine-Tuning (GiFT), a novel self-training method inspired by Gibbs sampling. GiFT allows self-generated data to be drawn from the marginal distribution of the joint space, thereby mitigating the biases inherent in conditional sampling. We provide a theoretical analysis demonstrating the potential benefits of fine-tuning LLMs with code derived from the marginal distribution. Furthermore, we propose a perplexity-based code selection method to mitigate the imbalanced long-tail distribution of the self-generated codes. Empirical evaluation of two LLMs across four datasets demonstrates that GiFT achieves superior performance, particularly on more challenging benchmarks. Source code is available at https://github.com/Alex-HaochenLi/GiFT.
