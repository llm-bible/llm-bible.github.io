---
layout: publication
title: 'Demonstration Selection For In-context Learning Via Reinforcement Learning'
authors: Xubin Wang, Jianfei Wu, Yichen Yuan, Deyu Cai, Mingzhe Li, Weijia Jia
conference: "Arxiv"
year: 2024
bibkey: wang2024demonstration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.03966"}
tags: ['Agentic', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'Prompting', 'In-Context Learning']
---
Diversity in demonstration selection is critical for enhancing model generalization by enabling broader coverage of structures and concepts. Constructing appropriate demonstration sets remains a key research challenge. This paper introduces the Relevance-Diversity Enhanced Selection (RDES), an innovative approach that leverages reinforcement learning (RL) frameworks to optimize the selection of diverse reference demonstrations for tasks amenable to in-context learning (ICL), particularly text classification and reasoning, in few-shot prompting scenarios. RDES employs frameworks like Q-learning and a PPO-based variant to dynamically identify demonstrations that maximize both diversity (quantified by label distribution) and relevance to the task objective. This strategy ensures a balanced representation of reference data, leading to improved accuracy and generalization. Through extensive experiments on multiple benchmark datasets, including diverse reasoning tasks, and involving 14 closed-source and open-source LLMs, we demonstrate that RDES significantly enhances performance compared to ten established baselines. Our evaluation includes analysis of performance across varying numbers of demonstrations on selected datasets. Furthermore, we investigate incorporating Chain-of-Thought (CoT) reasoning, which further boosts predictive performance. The results highlight the potential of RL for adaptive demonstration selection and addressing challenges in ICL.
