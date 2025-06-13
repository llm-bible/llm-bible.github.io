---
layout: publication
title: 'ICPL: Few-shot In-context Preference Learning Via Llms'
authors: Chao Yu, Qixin Tan, Hong Lu, Jiaxuan Gao, Xinting Yang, Yu Wang, Yi Wu, Eugene Vinitsky
conference: "Arxiv"
year: 2024
bibkey: yu2024few
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17233'}
tags: ['Agentic', 'Few-Shot', 'Efficiency and Optimization', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Preference-based reinforcement learning is an effective way to handle tasks
where rewards are hard to specify but can be exceedingly inefficient as
preference learning is often tabula rasa. We demonstrate that Large Language
Models (LLMs) have native preference-learning capabilities that allow them to
achieve sample-efficient preference learning, addressing this challenge. We
propose In-Context Preference Learning (ICPL), which uses in-context learning
capabilities of LLMs to reduce human query inefficiency. ICPL uses the task
description and basic environment code to create sets of reward functions which
are iteratively refined by placing human feedback over videos of the resultant
policies into the context of an LLM and then requesting better rewards. We
first demonstrate ICPL's effectiveness through a synthetic preference study,
providing quantitative evidence that it significantly outperforms baseline
preference-based methods with much higher performance and orders of magnitude
greater efficiency. We observe that these improvements are not solely coming
from LLM grounding in the task but that the quality of the rewards improves
over time, indicating preference learning capabilities. Additionally, we
perform a series of real human preference-learning trials and observe that ICPL
extends beyond synthetic settings and can work effectively with
humans-in-the-loop.
