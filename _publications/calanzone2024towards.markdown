---
layout: publication
title: Towards Logically Consistent Language Models Via Probabilistic Reasoning
authors: Calanzone Diego, Teso Stefano, Vergari Antonio
conference: "Arxiv"
year: 2024
bibkey: calanzone2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12843"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) are a promising venue for natural language understanding and generation tasks. However current LLMs are far from reliable they are prone to generate non45;factual information and more crucially to contradict themselves when prompted to reason about beliefs of the world. These problems are currently addressed with large scale fine45;tuning or by delegating consistent reasoning to external tools. In this work we strive for a middle ground and introduce a training objective based on principled probabilistic reasoning that teaches a LLM to be consistent with external knowledge in the form of a set of facts and rules. Fine45;tuning with our loss on a limited set of facts enables our LLMs to be more logically consistent than previous baselines and allows them to extrapolate to unseen but semantically similar factual knowledge more systematically.
