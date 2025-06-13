---
layout: publication
title: 'Weak-for-strong: Training Weak Meta-agent To Harness Strong Executors'
authors: Fan Nie, Lan Feng, Haotian Ye, Weixin Liang, Pan Lu, Huaxiu Yao, Alexandre Alahi, James Zou
conference: "Arxiv"
year: 2025
bibkey: nie2025weak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04785"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Efficiency and Optimization', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Efficiently leveraging of the capabilities of contemporary large language
models (LLMs) is increasingly challenging, particularly when direct fine-tuning
is expensive and often impractical. Existing training-free methods, including
manually or automated designed workflows, typically demand substantial human
effort or yield suboptimal results. This paper proposes Weak-for-Strong
Harnessing (W4S), a novel framework that customizes smaller, cost-efficient
language models to design and optimize workflows for harnessing stronger
models. W4S formulates workflow design as a multi-turn markov decision process
and introduces reinforcement learning for agentic workflow optimization (RLAO)
to train a weak meta-agent. Through iterative interaction with the environment,
the meta-agent learns to design increasingly effective workflows without manual
intervention. Empirical results demonstrate the superiority of W4S that our 7B
meta-agent, trained with just one GPU hour, outperforms the strongest baseline
by 2.9% ~ 24.6% across eleven benchmarks, successfully elevating the
performance of state-of-the-art models such as GPT-3.5-Turbo and GPT-4o.
Notably, W4S exhibits strong generalization capabilities across both seen and
unseen tasks, offering an efficient, high-performing alternative to directly
fine-tuning strong models.
