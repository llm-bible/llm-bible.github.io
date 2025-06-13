---
layout: publication
title: 'Leanpo: Lean Preference Optimization For Likelihood Alignment In Video-llms'
authors: Xiaodong Wang, Jinfa Huang, Li Yuan, Peixi Peng
conference: "Arxiv"
year: 2025
bibkey: wang2025lean
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.05260"}
tags: ['RAG', 'Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Most Video Large Language Models (Video-LLMs) adopt preference alignment techniques, e.g., DPO~\citep\{rafailov2024dpo\}, to optimize the reward margin between a winning response (\\(y_w\\)) and a losing response (\\(y_l\\)). However, the likelihood displacement observed in DPO indicates that both \\(log \pi_\theta (y_w\mid x)\\) and \\(log \pi_\theta (y_l\mid x) \\) often decrease during training, inadvertently boosting the probabilities of non-target responses. In this paper, we systematically revisit this phenomenon from LLMs to Video-LLMs, showing that it intensifies when dealing with the redundant complexity of video content. To alleviate the impact of this phenomenon, we propose *Lean Preference Optimization* (LeanPO), a reference-free approach that reformulates the implicit reward as the average likelihood of the response with respect to the policy model. A key component of LeanPO is the reward-trustworthiness correlated self-generated preference data pipeline, which carefully infuses relevant prior knowledge into the model while continuously refining the preference data via self-reflection. This allows the policy model to obtain high-quality paired data and accurately estimate the newly defined reward, thus mitigating the unintended drop. In addition, we introduce a dynamic label smoothing strategy that mitigates the impact of noise in responses from diverse video content, preventing the model from overfitting to spurious details. Extensive experiments demonstrate that LeanPO significantly enhances the performance of state-of-the-art Video-LLMs, consistently boosting baselines of varying capacities with minimal additional training overhead. Moreover, LeanPO offers a simple yet effective solution for aligning Video-LLM preferences with human trustworthiness, paving the way toward the reliable and efficient Video-LLMs.
