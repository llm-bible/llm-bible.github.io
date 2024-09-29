---
layout: publication
title: Dialogue For Prompting A Policy45;gradient45;based Discrete Prompt Generation For Few45;shot Learning
authors: Li Chengzhengxu, Liu Xiaoming, Wang Yichen, Li Duyi, Lan Yu, Shen Chao
conference: "Arxiv"
year: 2023
bibkey: li2023dialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.07272"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Prompt45;based pre45;trained language models (PLMs) paradigm have succeeded substantially in few45;shot natural language processing (NLP) tasks. However prior discrete prompt optimization methods require expert knowledge to design the base prompt set and identify high45;quality prompts which is costly inefficient and subjective. Meanwhile existing continuous prompt optimization methods improve the performance by learning the ideal prompts through the gradient information of PLMs whose high computational cost and low readability and generalizability are often concerning. To address the research gap we propose a Dialogue45;comprised Policy45;gradient45;based Discrete Prompt Optimization (DP95;2O) method. We first design a multi45;round dialogue alignment strategy for readability prompt set generation based on GPT45;4. Furthermore we propose an efficient prompt screening metric to identify high45;quality prompts with linear complexity. Finally we construct a reinforcement learning (RL) framework based on policy gradients to match the prompts to inputs optimally. By training a policy network with only 0.6737; of the PLM parameter size on the tasks in the few45;shot setting DP95;2O outperforms the state45;of45;the45;art (SOTA) method by 1.5237; in accuracy on average on four open45;source datasets. Moreover subsequent experiments also demonstrate that DP95;2O has good universality robustness and generalization ability.
