---
layout: publication
title: 'The Perfect Blend: Redefining RLHF With Mixture Of Judges'
authors: Tengyu Xu, Eryk Helenowski, Karthik Abinav Sankararaman, Di Jin, Kaiyan Peng, Eric Han, Shaoliang Nie, Chen Zhu, Hejia Zhang, Wenxuan Zhou, Zhouhao Zeng, Yun He, Karishma Mandyam, Arya Talabzadeh, Madian Khabsa, Gabriel Cohen, Yuandong Tian, Hao Ma, Sinong Wang, Han Fang
conference: "Arxiv"
year: 2024
bibkey: xu2024perfect
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.20370"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Reinforcement learning from human feedback (RLHF) has become the leading
approach for fine-tuning large language models (LLM). However, RLHF has
limitations in multi-task learning (MTL) due to challenges of reward hacking
and extreme multi-objective optimization (i.e., trade-off of multiple and/or
sometimes conflicting objectives). Applying RLHF for MTL currently requires
careful tuning of the weights for reward model and data combinations. This is
often done via human intuition and does not generalize. In this work, we
introduce a novel post-training paradigm which we called Constrained Generative
Policy Optimization (CGPO). The core of CGPO is Mixture of Judges (MoJ) with
cost-efficient constrained policy optimization with stratification, which can
identify the perfect blend in RLHF in a principled manner. It shows strong
empirical results with theoretical guarantees, does not require extensive
hyper-parameter tuning, and is plug-and-play in common post-training pipelines.
Together, this can detect and mitigate reward hacking behaviors while reaching
a pareto-optimal point across an extremely large number of objectives.
  Our empirical evaluations demonstrate that CGPO significantly outperforms
standard RLHF algorithms like PPO and DPO across various tasks including
general chat, STEM questions, instruction following, and coding. Specifically,
CGPO shows improvements of 7.4% in AlpacaEval-2 (general chat), 12.5% in
Arena-Hard (STEM & reasoning), and consistent gains in other domains like math
and coding. Notably, PPO, while commonly used, is prone to severe reward
hacking in popular coding benchmarks, which CGPO successfully addresses. This
breakthrough in RLHF not only tackles reward hacking and extreme
multi-objective optimization challenges but also advances the state-of-the-art
in aligning general-purpose LLMs for diverse applications.
