---
layout: publication
title: 'Hf4rec: Human-like Feedback-driven Optimization Framework For Explainable Recommendation'
authors: Jiakai Tang, Jingsen Zhang, Zihang Tian, Xueyang Feng, Lei Wang, Xu Chen
conference: "Arxiv"
year: 2025
bibkey: tang2025human
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14147"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability and Explainability']
---
Recent advancements in explainable recommendation have greatly bolstered user
experience by elucidating the decision-making rationale. However, the existing
methods actually fail to provide effective feedback signals for potentially
better or worse generated explanations due to their reliance on traditional
supervised learning paradigms in sparse interaction data. To address these
issues, we propose a novel human-like feedback-driven optimization framework.
This framework employs a dynamic interactive optimization mechanism for
achieving human-centered explainable requirements without incurring high labor
costs. Specifically, we propose to utilize large language models (LLMs) as
human simulators to predict human-like feedback for guiding the learning
process. To enable the LLMs to deeply understand the task essence and meet
user's diverse personalized requirements, we introduce a human-induced
customized reward scoring method, which helps stimulate the language
understanding and logical reasoning capabilities of LLMs. Furthermore,
considering the potential conflicts between different perspectives of
explanation quality, we introduce a principled Pareto optimization that
transforms the multi-perspective quality enhancement task into a
multi-objective optimization problem for improving explanation performance. At
last, to achieve efficient model training, we design an off-policy optimization
pipeline. By incorporating a replay buffer and addressing the data distribution
biases, we can effectively improve data utilization and enhance model
generality. Extensive experiments on four datasets demonstrate the superiority
of our approach.
