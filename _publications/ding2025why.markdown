---
layout: publication
title: 'Why Not Act On What You Know? Unleashing Safety Potential Of Llms Via Self-aware Guard Enhancement'
authors: Peng Ding, Jun Kuang, Zongyu Wang, Xuezhi Cao, Xunliang Cai, Jiajun Chen, Shujian Huang
conference: "Arxiv"
year: 2025
bibkey: ding2025why
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12060"}
  - {name: "Code", url: "https://github.com/NJUNLP/SAGE"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Has Code', 'Interpretability and Explainability', 'Prompting', 'Attention Mechanism']
---
Large Language Models (LLMs) have shown impressive capabilities across various tasks but remain vulnerable to meticulously crafted jailbreak attacks. In this paper, we identify a critical safety gap: while LLMs are adept at detecting jailbreak prompts, they often produce unsafe responses when directly processing these inputs. Inspired by this insight, we propose SAGE (Self-Aware Guard Enhancement), a training-free defense strategy designed to align LLMs' strong safety discrimination performance with their relatively weaker safety generation ability. SAGE consists of two core components: a Discriminative Analysis Module and a Discriminative Response Module, enhancing resilience against sophisticated jailbreak attempts through flexible safety discrimination instructions. Extensive experiments demonstrate SAGE's effectiveness and robustness across various open-source and closed-source LLMs of different sizes and architectures, achieving an average 99% defense success rate against numerous complex and covert jailbreak methods while maintaining helpfulness on general benchmarks. We further conduct mechanistic interpretability analysis through hidden states and attention distributions, revealing the underlying mechanisms of this detection-generation discrepancy. Our work thus contributes to developing future LLMs with coherent safety awareness and generation behavior. Our code and datasets are publicly available at https://github.com/NJUNLP/SAGE.
