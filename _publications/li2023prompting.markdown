---
layout: publication
title: 'Prompting Large Language Models For Counterfactual Generation: An Empirical Study'
authors: Li Yongqi, Xu Mayi, Miao Xin, Zhou Shen, Qian Tieyun
conference: "Arxiv"
year: 2023
bibkey: li2023prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14791"}
tags: ['Agentic', 'Applications', 'Ethics And Bias', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have made remarkable progress in a wide range of natural language understanding and generation tasks. However, their ability to generate counterfactuals has not been examined systematically. To bridge this gap, we present a comprehensive evaluation framework on various types of NLU tasks, which covers all key factors in determining LLMs' capability of generating counterfactuals. Based on this framework, we 1) investigate the strengths and weaknesses of LLMs as the counterfactual generator, and 2) disclose the factors that affect LLMs when generating counterfactuals, including both the intrinsic properties of LLMs and prompt designing. The results show that, though LLMs are promising in most cases, they face challenges in complex tasks like RE since they are bounded by task-specific performance, entity constraints, and inherent selection bias. We also find that alignment techniques, e.g., instruction-tuning and reinforcement learning from human feedback, may potentially enhance the counterfactual generation ability of LLMs. On the contrary, simply increasing the parameter size does not yield the desired improvements. Besides, from the perspective of prompt designing, task guidelines unsurprisingly play an important role. However, the chain-of-thought approach does not always help due to inconsistency issues.
