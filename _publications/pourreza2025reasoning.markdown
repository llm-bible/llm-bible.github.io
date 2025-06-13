---
layout: publication
title: 'Reasoning-sql: Reinforcement Learning With SQL Tailored Partial Rewards For Reasoning-enhanced Text-to-sql'
authors: Mohammadreza Pourreza, Shayan Talaei, Ruoxi Sun, Xingchen Wan, Hailong Li, Azalia Mirhoseini, Amin Saberi, Sercan "o. Arik
conference: "Arxiv"
year: 2025
bibkey: pourreza2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23157"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'Ethics and Bias', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Text-to-SQL is a challenging task involving multiple reasoning-intensive
subtasks, including natural language understanding, database schema
comprehension, and precise SQL query formulation. Existing approaches often
rely on handcrafted reasoning paths with inductive biases that can limit their
overall effectiveness. Motivated by the recent success of reasoning-enhanced
models such as DeepSeek R1 and OpenAI o1, which effectively leverage
reward-driven self-exploration to enhance reasoning capabilities and
generalization, we propose a novel set of partial rewards tailored specifically
for the Text-to-SQL task. Our reward set includes schema-linking, AI feedback,
n-gram similarity, and syntax check, explicitly designed to address the reward
sparsity issue prevalent in reinforcement learning (RL). Leveraging group
relative policy optimization (GRPO), our approach explicitly encourages large
language models (LLMs) to develop intrinsic reasoning skills necessary for
accurate SQL query generation. With models of different sizes, we demonstrate
that RL-only training with our proposed rewards consistently achieves higher
accuracy and superior generalization compared to supervised fine-tuning (SFT).
Remarkably, our RL-trained 14B-parameter model significantly outperforms larger
proprietary models, e.g. o3-mini by 4% and Gemini-1.5-Pro-002 by 3% on the BIRD
benchmark. These highlight the efficacy of our proposed RL-training framework
with partial rewards for enhancing both accuracy and reasoning capabilities in
Text-to-SQL tasks.
