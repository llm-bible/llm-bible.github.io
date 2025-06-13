---
layout: publication
title: 'Flame-moe: A Transparent End-to-end Research Platform For Mixture-of-experts Language Models'
authors: Hao Kang, Zichun Yu, Chenyan Xiong
conference: "Arxiv"
year: 2025
bibkey: kang2025flame
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20225"}
  - {name: "Code", url: "https://github.com/cmu-flame/FLAME-MoE"}
tags: ['Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Interpretability', 'Training Techniques', 'Has Code']
---
Recent large language models such as Gemini-1.5, DeepSeek-V3, and Llama-4 increasingly adopt Mixture-of-Experts (MoE) architectures, which offer strong efficiency-performance trade-offs by activating only a fraction of the model per token. Yet academic researchers still lack a fully open, end-to-end MoE platform for investigating scaling, routing, and expert behavior. We release FLAME-MoE, a completely open-source research suite composed of seven decoder-only models, ranging from 38M to 1.7B active parameters, whose architecture--64 experts with top-8 gating and 2 shared experts--closely reflects modern production LLMs. All training data pipelines, scripts, logs, and checkpoints are publicly available to enable reproducible experimentation. Across six evaluation tasks, FLAME-MoE improves average accuracy by up to 3.4 points over dense baselines trained with identical FLOPs. Leveraging full training trace transparency, we present initial analyses showing that (i) experts increasingly specialize on distinct token subsets, (ii) co-activation matrices remain sparse, reflecting diverse expert usage, and (iii) routing behavior stabilizes early in training. All code, training logs, and model checkpoints are available at https://github.com/cmu-flame/FLAME-MoE.
