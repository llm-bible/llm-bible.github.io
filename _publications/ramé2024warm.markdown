---
layout: publication
title: WARM On the Benefits of Weight Averaged Reward Models
authors: Ramé Alexandre, Vieillard Nino, Hussenot Léonard, Dadashi Robert, Cideron Geoffrey, Bachem Olivier, Ferret Johan
conference: "Arxiv"
year: 2024
bibkey: ramé2024warm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12187"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Aligning large language models (LLMs) with human preferences through reinforcement learning (RLHF) can lead to reward hacking where LLMs exploit failures in the reward model (RM) to achieve seemingly high rewards without meeting the underlying objectives. We identify two primary challenges when designing RMs to mitigate reward hacking distribution shifts during the RL process and inconsistencies in human preferences. As a solution we propose Weight Averaged Reward Models (WARM) first fine-tuning multiple RMs then averaging them in the weight space. This strategy follows the observation that fine-tuned weights remain linearly mode connected when sharing the same pre-training. By averaging weights WARM improves efficiency compared to the traditional ensembling of predictions while improving reliability under distribution shifts and robustness to preference inconsistencies. Our experiments on summarization tasks using best-of-N and RL methods shows that WARM improves the overall quality and alignment of LLM predictions; for example a policy RL fine-tuned with WARM has a 79.4 win rate against a policy RL fine-tuned with a single RM.
