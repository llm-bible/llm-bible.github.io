---
layout: publication
title: 'Freeprm: Training Process Reward Models Without Ground Truth Process Labels'
authors: Lin Sun, Chuang Liu, Xiaofeng Ma, Tao Yang, Weijia Lu, Ning Wu
conference: "Arxiv"
year: 2025
bibkey: sun2025training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03570"}
tags: ['RAG', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Recent advancements in Large Language Models (LLMs) have demonstrated that Process Reward Models (PRMs) play a crucial role in enhancing model performance. However, training PRMs typically requires step-level labels, either manually annotated or automatically generated, which can be costly and difficult to obtain at scale. To address this challenge, we introduce FreePRM, a weakly supervised framework for training PRMs without access to ground-truth step-level labels. FreePRM first generates pseudo step-level labels based on the correctness of final outcome, and then employs Buffer Probability to eliminate impact of noise inherent in pseudo labeling. Experimental results show that FreePRM achieves an average F1 score of 53.0% on ProcessBench, outperforming fully supervised PRM trained on Math-Shepherd by +24.1%. Compared to other open-source PRMs, FreePRM outperforms upon RLHFlow-PRM-Mistral-8B (28.4%) by +24.6%, EurusPRM (31.3%) by +21.7%, and Skywork-PRM-7B (42.1%) by +10.9%. This work introduces a new paradigm in PRM training, significantly reducing reliance on costly step-level annotations while maintaining strong performance.
