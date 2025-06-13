---
layout: publication
title: 'Towards Interpretable Soft Prompts'
authors: Oam Patel, Jason Wang, Nikhil Shivakumar Nayak, Suraj Srinivas, Himabindu Lakkaraju
conference: "Arxiv"
year: 2025
bibkey: patel2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02144"}
tags: ['Tools', 'GPT', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Few-Shot', 'Prompting']
---
Soft prompts have been popularized as a cheap and easy way to improve
task-specific LLM performance beyond few-shot prompts. Despite their origin as
an automated prompting method, however, soft prompts and other trainable
prompts remain a black-box method with no immediately interpretable connections
to prompting. We create a novel theoretical framework for evaluating the
interpretability of trainable prompts based on two desiderata: faithfulness and
scrutability. We find that existing methods do not naturally satisfy our
proposed interpretability criterion. Instead, our framework inspires a new
direction of trainable prompting methods that explicitly optimizes for
interpretability. To this end, we formulate and test new
interpretability-oriented objective functions for two state-of-the-art prompt
tuners: Hard Prompts Made Easy (PEZ) and RLPrompt. Our experiments with GPT-2
demonstrate a fundamental trade-off between interpretability and the
task-performance of the trainable prompt, explicating the hardness of the soft
prompt interpretability problem and revealing odd behavior that arises when one
optimizes for an interpretability proxy.
