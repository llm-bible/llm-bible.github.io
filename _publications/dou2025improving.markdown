---
layout: publication
title: 'Improving RL Exploration For LLM Reasoning Through Retrospective Replay'
authors: Shihan Dou, Muling Wu, Jingwen Xu, Rui Zheng, Tao Gui, Qi Zhang, Xuanjing Huang
conference: "Arxiv"
year: 2025
bibkey: dou2025improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14363'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning']
---
Reinforcement learning (RL) has increasingly become a pivotal technique in
the post-training of large language models (LLMs). The effective exploration of
the output space is essential for the success of RL. We observe that for
complex problems, during the early stages of training, the model exhibits
strong exploratory capabilities and can identify promising solution ideas.
However, its limited capability at this stage prevents it from successfully
solving these problems. The early suppression of these potentially valuable
solution ideas by the policy gradient hinders the model's ability to revisit
and re-explore these ideas later. Consequently, although the LLM's capabilities
improve in the later stages of training, it still struggles to effectively
address these complex problems. To address this exploration issue, we propose a
novel algorithm named Retrospective Replay-based Reinforcement Learning (RRL),
which introduces a dynamic replay mechanism throughout the training process.
RRL enables the model to revisit promising states identified in the early
stages, thereby improving its efficiency and effectiveness in exploration. To
evaluate the effectiveness of RRL, we conduct extensive experiments on complex
reasoning tasks, including mathematical reasoning and code generation, and
general dialogue tasks. The results indicate that RRL maintains high
exploration efficiency throughout the training period, significantly enhancing
the effectiveness of RL in optimizing LLMs for complicated reasoning tasks.
Moreover, it also improves the performance of RLHF, making the model both safer
and more helpful.
