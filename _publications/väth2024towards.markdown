---
layout: publication
title: 'Towards Zero-shot, Controllable Dialog Planning With Llms'
authors: Dirk Väth, Ngoc Thang Vu
conference: "Arxiv"
year: 2024
bibkey: väth2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05821"}
tags: ['Agentic', 'Efficiency and Optimization', 'Pruning', 'Reinforcement Learning', 'Training Techniques']
---
Recently, Large Language Models (LLMs) have emerged as an alternative to
training task-specific dialog agents, due to their broad reasoning capabilities
and performance in zero-shot learning scenarios. However, many LLM-based dialog
systems fall short in planning towards an overarching dialog goal and therefore
cannot steer the conversation appropriately. Furthermore, these models struggle
with hallucination, making them unsuitable for information access in sensitive
domains, such as legal or medical domains, where correctness of information
given to users is critical. The recently introduced task Conversational Tree
Search (CTS) proposes the use of dialog graphs to avoid hallucination in
sensitive domains, however, state-of-the-art agents are Reinforcement Learning
(RL) based and require long training times, despite excelling at dialog
strategy. This paper introduces a novel zero-shot method for controllable CTS
agents, where LLMs guide the dialog planning through domain graphs by searching
and pruning relevant graph nodes based on user interaction preferences. We show
that these agents significantly outperform state-of-the-art CTS agents
(\\(p<0.0001\\); Barnard Exact test) in simulation. This generalizes to all
available CTS domains. Finally, we perform user evaluation to test the agent's
performance in the wild, showing that our policy significantly (\\(p<0.05\\);
Barnard Exact) improves task-success compared to the state-of-the-art RL-based
CTS agent.
