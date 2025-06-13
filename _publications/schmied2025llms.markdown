---
layout: publication
title: 'Llms Are Greedy Agents: Effects Of RL Fine-tuning On Decision-making Abilities'
authors: Thomas Schmied, Jörg Bornschein, Jordi Grau-moya, Markus Wulfmeier, Razvan Pascanu
conference: "Arxiv"
year: 2025
bibkey: schmied2025llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16078"}
tags: ['Fine-Tuning', 'Agentic', 'Ethics and Bias', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
The success of Large Language Models (LLMs) has sparked interest in various
agentic applications. A key hypothesis is that LLMs, leveraging common sense
and Chain-of-Thought (CoT) reasoning, can effectively explore and efficiently
solve complex domains. However, LLM agents have been found to suffer from
sub-optimal exploration and the knowing-doing gap, the inability to effectively
act on knowledge present in the model. In this work, we systematically study
why LLMs perform sub-optimally in decision-making scenarios. In particular, we
closely examine three prevalent failure modes: greediness, frequency bias, and
the knowing-doing gap. We propose mitigation of these shortcomings by
fine-tuning via Reinforcement Learning (RL) on self-generated CoT rationales.
Our experiments across multi-armed bandits, contextual bandits, and
Tic-tac-toe, demonstrate that RL fine-tuning enhances the decision-making
abilities of LLMs by increasing exploration and narrowing the knowing-doing
gap. Finally, we study both classic exploration mechanisms, such as
\\(\epsilon\\)-greedy, and LLM-specific approaches, such as self-correction and
self-consistency, to enable more effective fine-tuning of LLMs for
decision-making.
