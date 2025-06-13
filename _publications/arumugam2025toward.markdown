---
layout: publication
title: 'Toward Efficient Exploration By Large Language Model Agents'
authors: Dilip Arumugam, Thomas L. Griffiths
conference: "Arxiv"
year: 2025
bibkey: arumugam2025toward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20997"}
tags: ['Agentic', 'Efficiency and Optimization', 'Reinforcement Learning', 'TACL', 'Fine-Tuning', 'ACL', 'Applications']
---
A burgeoning area within reinforcement learning (RL) is the design of
sequential decision-making agents centered around large language models (LLMs).
While autonomous decision-making agents powered by modern LLMs could facilitate
numerous real-world applications, such successes demand agents that are capable
of data-efficient RL. One key obstacle to achieving data efficiency in RL is
exploration, a challenge that we demonstrate many recent proposals for LLM
agent designs struggle to contend with. Meanwhile, classic algorithms from the
RL literature known to gracefully address exploration require technical
machinery that can be challenging to operationalize in purely natural language
settings. In this work, rather than relying on finetuning or in-context
learning to coax LLMs into implicitly imitating a RL algorithm, we illustrate
how LLMs can be used to explicitly implement an existing RL algorithm
(Posterior Sampling for Reinforcement Learning) whose capacity for
statistically-efficient exploration is already well-studied. We offer empirical
results demonstrating how our LLM-based implementation of a known,
data-efficient RL algorithm can be considerably more effective in natural
language tasks that demand prudent exploration.
