---
layout: publication
title: 'Controlling Large Language Model Agents With Entropic Activation Steering'
authors: Nate Rahn, Pierluca D'oro, Marc G. Bellemare
conference: "Arxiv"
year: 2024
bibkey: rahn2024controlling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00244"}
tags: ['Prompting', 'Agentic', 'Fine-Tuning', 'In-Context Learning']
---
The rise of large language models (LLMs) has prompted increasing interest in
their use as in-context learning agents. At the core of agentic behavior is the
capacity for exploration, or the ability to actively gather information about
the environment. But how do LLM agents explore, and how can we control their
exploratory behaviors? To answer these questions, we take a
representation-level perspective, and introduce Entropic Activation Steering
(EAST), an activation steering method for in-context LLM agents. Firstly, we
demonstrate that EAST can effectively manipulate an LLM agent's exploration by
directly affecting the high-level actions parsed from the outputs of the LLM,
in contrast to token-level temperature sampling. Secondly, we reveal how
applying this control modulates the uncertainty exhibited in the LLM's
thoughts, guiding the agent towards more exploratory actions. Finally, we
demonstrate that the steering vectors obtained by EAST generalize across task
variants. In total, these results show that LLM agents explicitly encode
uncertainty over their actions in their representation space. Our work paves
the way for a new understanding of the functioning of LLM agents and to
effective control of their decision-making behaviors.
