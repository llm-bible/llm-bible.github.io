---
layout: publication
title: 'Towards Efficient And Effective Unlearning Of Large Language Models For Recommendation'
authors: Wang Hangyu, Lin Jianghao, Chen Bo, Yang Yang, Tang Ruiming, Zhang Weinan, Yu Yong
conference: "Arxiv"
year: 2024
bibkey: wang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03536"}
  - {name: "Code", url: "https://github.com/justarter/E2URec"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
'The significant advancements in large language models (LLMs) give rise to a promising research direction, i.e., leveraging LLMs as recommenders (LLMRec). The efficacy of LLMRec arises from the open-world knowledge and reasoning capabilities inherent in LLMs. LLMRec acquires the recommendation capabilities through instruction tuning based on user interaction data. However, in order to protect user privacy and optimize utility, it is also crucial for LLMRec to intentionally forget specific user data, which is generally referred to as recommendation unlearning. In the era of LLMs, recommendation unlearning poses new challenges for LLMRec in terms of \textit\{inefficiency\} and \textit\{ineffectiveness\}. Existing unlearning methods require updating billions of parameters in LLMRec, which is costly and time-consuming. Besides, they always impact the model utility during the unlearning process. To this end, we propose \textbf\{E2URec\}, the first \underline\{E\}fficient and \underline\{E\}ffective \underline\{U\}nlearning method for LLM\underline\{Rec\}. Our proposed E2URec enhances the unlearning efficiency by updating only a few additional LoRA parameters, and improves the unlearning effectiveness by employing a teacher-student framework, where we maintain multiple teacher networks to guide the unlearning process. Extensive experiments show that E2URec outperforms state-of-the-art baselines on two real-world datasets. Specifically, E2URec can efficiently forget specific data without affecting recommendation performance. The source code is at \url\{https://github.com/justarter/E2URec\}.'
