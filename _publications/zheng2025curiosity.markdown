---
layout: publication
title: 'CALM: Curiosity-driven Auditing For Large Language Models'
authors: Xiang Zheng, Longxiang Wang, Yi Liu, Xingjun Ma, Chao Shen, Cong Wang
conference: "Arxiv"
year: 2025
bibkey: zheng2025curiosity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02997"}
  - {name: "Code", url: "https://github.com/x-zheng16/CALM.git"}
tags: ['Agentic', 'Efficiency and Optimization', 'Reinforcement Learning', 'Ethics and Bias', 'Has Code', 'Prompting']
---
Auditing Large Language Models (LLMs) is a crucial and challenging task. In
this study, we focus on auditing black-box LLMs without access to their
parameters, only to the provided service. We treat this type of auditing as a
black-box optimization problem where the goal is to automatically uncover
input-output pairs of the target LLMs that exhibit illegal, immoral, or unsafe
behaviors. For instance, we may seek a non-toxic input that the target LLM
responds to with a toxic output or an input that induces the hallucinative
response from the target LLM containing politically sensitive individuals. This
black-box optimization is challenging due to the scarcity of feasible points,
the discrete nature of the prompt space, and the large search space. To address
these challenges, we propose Curiosity-Driven Auditing for Large Language
Models (CALM), which uses intrinsically motivated reinforcement learning to
finetune an LLM as the auditor agent to uncover potential harmful and biased
input-output pairs of the target LLM. CALM successfully identifies derogatory
completions involving celebrities and uncovers inputs that elicit specific
names under the black-box setting. This work offers a promising direction for
auditing black-box LLMs. Our code is available at
https://github.com/x-zheng16/CALM.git.
