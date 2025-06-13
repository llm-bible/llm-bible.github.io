---
layout: publication
title: 'Scalable Reinforcement Post-training Beyond Static Human Prompts: Evolving Alignment Via Asymmetric Self-play'
authors: Ziyu Ye, Rishabh Agarwal, Tianqi Liu, Rishabh Joshi, Sarmishta Velury, Quoc V. Le, Qijun Tan, Yuan Liu
conference: "Arxiv"
year: 2024
bibkey: ye2024scalable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00062'}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Current reinforcement learning (RL) frameworks for large language models
(LLM) post-training typically assume a fixed prompt distribution, which is
sub-optimal and bottlenecks scalability. Prior works have explored prompt
evolving, but are often limited to the supervised fine-tuning stage, and
prompts are sampled and evolved uniformly without signals. This empirical work
presents a paradigm shift: Evolving Alignment via Asymmetric Self-Play (eva),
that casts post-training as an infinite game with regret-based signals for 2
players: (i) a creator, who strategically samples and creates new informative
prompts and (ii) a solver, who learns to produce preferred responses. eva is
the first method that allows language models to adaptively create training
prompts in both offline and online RL post-training. The design is simple,
easy-to-use yet remarkably effective: eva sets a new SOTA on challenging
benchmarks, without any extra human prompts, e.g. it boosts the win-rate of
gemma-2-9b-it on Arena-Hard by 51.6% -> 60.1% for DPO and 52.6% -> 62.4% for
RLOO, surpassing claude-3-opus and catching up to gemini-1.5-pro, both of which
are orders of magnitude larger. Extensive experiments show eva can create
effective RL curricula and is robust across ablations. We believe adaptively
evolving prompts are key to designing the next-generation RL post-training
scheme.
