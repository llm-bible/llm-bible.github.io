---
layout: publication
title: Towards Efficient And Effective Unlearning Of Large Language Models For Recommendation
authors: Wang Hangyu, Lin Jianghao, Chen Bo, Yang Yang, Tang Ruiming, Zhang Weinan, Yu Yong
conference: "Arxiv"
year: 2024
bibkey: wang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03536"}
  - {name: "Code", url: "https://github.com/justarter/E2URec&#125;"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
The significant advancements in large language models (LLMs) give rise to a promising research direction i.e. leveraging LLMs as recommenders (LLMRec). The efficacy of LLMRec arises from the open45;world knowledge and reasoning capabilities inherent in LLMs. LLMRec acquires the recommendation capabilities through instruction tuning based on user interaction data. However in order to protect user privacy and optimize utility it is also crucial for LLMRec to intentionally forget specific user data which is generally referred to as recommendation unlearning. In the era of LLMs recommendation unlearning poses new challenges for LLMRec in terms of textit123;inefficiency125; and textit123;ineffectiveness125;. Existing unlearning methods require updating billions of parameters in LLMRec which is costly and time45;consuming. Besides they always impact the model utility during the unlearning process. To this end we propose textbf123;E2URec125; the first underline123;E125;fficient and underline123;E125;ffective underline123;U125;nlearning method for LLMunderline123;Rec125;. Our proposed E2URec enhances the unlearning efficiency by updating only a few additional LoRA parameters and improves the unlearning effectiveness by employing a teacher45;student framework where we maintain multiple teacher networks to guide the unlearning process. Extensive experiments show that E2URec outperforms state45;of45;the45;art baselines on two real45;world datasets. Specifically E2URec can efficiently forget specific data without affecting recommendation performance. The source code is at url123;https://github.com/justarter/E2URec&#125;.
