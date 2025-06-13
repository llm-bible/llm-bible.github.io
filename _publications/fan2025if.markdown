---
layout: publication
title: 'If An LLM Were A Character, Would It Know Its Own Story? Evaluating Lifelong Learning In Llms'
authors: Siqi Fan, Xiusheng Huang, Yiqun Yao, Xuezhi Fang, Kang Liu, Peng Han, Shuo Shang, Aixin Sun, Yequan Wang
conference: "Arxiv"
year: 2025
bibkey: fan2025if
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23514"}
tags: ['Agentic', 'Model Architecture', 'GPT']
---
Large language models (LLMs) can carry out human-like dialogue, but unlike
humans, they are stateless due to the superposition property. However, during
multi-turn, multi-agent interactions, LLMs begin to exhibit consistent,
character-like behaviors, hinting at a form of emergent lifelong learning.
Despite this, existing benchmarks often fail to capture these dynamics,
primarily focusing on static, open-ended evaluations. To address this gap, we
introduce LIFESTATE-BENCH, a benchmark designed to assess lifelong learning in
LLMs. It features two episodic datasets: Hamlet and a synthetic script
collection, rich in narrative structure and character interactions. Our fact
checking evaluation probes models' self-awareness, episodic memory retrieval,
and relationship tracking, across both parametric and non-parametric
approaches. Experiments on models like Llama3.1-8B, GPT-4-turbo, and DeepSeek
R1, we demonstrate that nonparametric methods significantly outperform
parametric ones in managing stateful learning. However, all models exhibit
challenges with catastrophic forgetting as interactions extend, highlighting
the need for further advancements in lifelong learning.
