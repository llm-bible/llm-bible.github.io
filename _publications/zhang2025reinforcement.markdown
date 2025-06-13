---
layout: publication
title: 'Reinforcement Learning For Better Verbalized Confidence In Long-form Generation'
authors: Caiqi Zhang, Xiaochen Zhu, Chengzu Li, Nigel Collier, Andreas Vlachos
conference: "Arxiv"
year: 2025
bibkey: zhang2025reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23912"}
tags: ['Agentic', 'Applications', 'Reinforcement Learning']
---
Hallucination remains a major challenge for the safe and trustworthy deployment of large language models (LLMs) in factual content generation. Prior work has explored confidence estimation as an effective approach to hallucination detection, but often relies on post-hoc self-consistency methods that require computationally expensive sampling. Verbalized confidence offers a more efficient alternative, but existing approaches are largely limited to short-form question answering (QA) tasks and do not generalize well to open-ended generation. In this paper, we propose LoVeC (Long-form Verbalized Confidence), an on-the-fly verbalized confidence estimation method for long-form generation. Specifically, we use reinforcement learning (RL) to train LLMs to append numerical confidence scores to each generated statement, serving as a direct and interpretable signal of the factuality of generation. Our experiments consider both on-policy and off-policy RL methods, including DPO, ORPO, and GRPO, to enhance the model calibration. We introduce two novel evaluation settings, free-form tagging and iterative tagging, to assess different verbalized confidence estimation methods. Experiments on three long-form QA datasets show that our RL-trained models achieve better calibration and generalize robustly across domains. Also, our method is highly efficient, as it only requires adding a few tokens to the output being decoded.
