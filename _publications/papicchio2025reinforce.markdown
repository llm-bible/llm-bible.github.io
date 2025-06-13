---
layout: publication
title: 'Think2sql: Reinforce LLM Reasoning Capabilities For Text2sql'
authors: Simone Papicchio, Simone Rossi, Luca Cagliero, Paolo Papotti
conference: "Arxiv"
year: 2025
bibkey: papicchio2025reinforce
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15077"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) have shown impressive capabilities in
transforming natural language questions about relational databases into SQL
queries. Despite recent improvements, small LLMs struggle to handle questions
involving multiple tables and complex SQL patterns under a Zero-Shot Learning
(ZSL) setting. Supervised Fine-Tuning (SFT) partially compensates for the
knowledge deficits in pretrained models but falls short while dealing with
queries involving multi-hop reasoning. To bridge this gap, different LLM
training strategies to reinforce reasoning capabilities have been proposed,
ranging from leveraging a thinking process within ZSL, including reasoning
traces in SFT, or adopt Reinforcement Learning (RL) strategies. However, the
influence of reasoning on Text2SQL performance is still largely unexplored.
This paper investigates to what extent LLM reasoning capabilities influence
their Text2SQL performance on four benchmark datasets. To this end, it
considers the following LLM settings: (1) ZSL, including general-purpose
reasoning or not; (2) SFT, with and without task-specific reasoning traces; (3)
RL, exploring the use of different rewarding functions, both the established
EXecution accuracy (EX) and a mix with fine-grained ones that also account the
precision, recall, and cardinality of partially correct answers; (4) SFT+RL,
i.e, a two-stage approach that combines SFT and RL. The results show that
general-purpose reasoning under ZSL proves to be ineffective in tackling
complex Text2SQL cases. Small LLMs benefit from SFT with reasoning much more
than larger ones. RL is generally beneficial across all tested models and
datasets. The use of the fine-grained metrics turns out to be the most
effective RL strategy. Thanks to RL and the novel text2SQL rewards, the 7B
Qwen-Coder-2.5 model performs on par with 400+ Billion ones (including gpt-4o)
on the Bird dataset.
