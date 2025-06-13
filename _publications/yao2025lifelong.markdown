---
layout: publication
title: 'Lilodriver: A Lifelong Learning Framework For Closed-loop Motion Planning In Long-tail Autonomous Driving Scenarios'
authors: Huaiyuan Yao, Pengfei Li, Bu Jin, Yupeng Zheng, An Liu, Lisen Mu, Qing Su, Qian Zhang, Yilun Chen, Peng Li
conference: "Arxiv"
year: 2025
bibkey: yao2025lifelong
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17209'}
  - {name: "Code", url: 'https://github.com/Hyan-Yao/LiloDriver'}
tags: ['Has Code', 'Model Architecture', 'Tools', 'Training Techniques', 'Reinforcement Learning']
---
Recent advances in autonomous driving research towards motion planners that are robust, safe, and adaptive. However, existing rule-based and data-driven planners lack adaptability to long-tail scenarios, while knowledge-driven methods offer strong reasoning but face challenges in representation, control, and real-world evaluation. To address these challenges, we present LiloDriver, a lifelong learning framework for closed-loop motion planning in long-tail autonomous driving scenarios. By integrating large language models (LLMs) with a memory-augmented planner generation system, LiloDriver continuously adapts to new scenarios without retraining. It features a four-stage architecture including perception, scene encoding, memory-based strategy refinement, and LLM-guided reasoning. Evaluated on the nuPlan benchmark, LiloDriver achieves superior performance in both common and rare driving scenarios, outperforming static rule-based and learning-based planners. Our results highlight the effectiveness of combining structured memory and LLM reasoning to enable scalable, human-like motion planning in real-world autonomous driving. Our code is available at https://github.com/Hyan-Yao/LiloDriver.
