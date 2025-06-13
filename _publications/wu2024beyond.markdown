---
layout: publication
title: 'Beyond Examples: High-level Automated Reasoning Paradigm In In-context Learning Via MCTS'
authors: Jinyang Wu, Mingkuan Feng, Shuai Zhang, Feihu Che, Zengqi Wen, Chonghua Liao, Jianhua Tao
conference: "Arxiv"
year: 2024
bibkey: wu2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18478"}
  - {name: "Code", url: "https://github.com/jinyangwu/HiARICL"}
tags: ['Efficiency and Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) enables large language models (LLMs) to perform downstream tasks through advanced prompting and high-quality demonstrations. However, traditional ICL paradigms encounter significant limitations in complex reasoning tasks, stemming primarily from their dependence on example quality and absence of explicit reasoning guidance. To address these challenges, we introduce HiAR-ICL, a **Hi**gh-level **A**utomated **R**easoning paradigm in **ICL** that shifts focus from specific examples to abstract reasoning patterns, thereby extending the conventional concept of "context" in ICL. Our approach begins by defining five atomic reasoning actions, upon which we employ Monte Carlo Tree Search to systematically construct high-level reasoning patterns. During inference, HiAR-ICL dynamically selects appropriate reasoning patterns based on problem attributes, providing explicit guidance for the model's reasoning process. Experiments demonstrate HiAR-ICL's effectiveness and efficiency: utilizing only 200 prior samples with Qwen2.5-7B-Instruct, our method achieves 80.6% accuracy on MATH and 62.5% on AMC, exceeding GPT-4o's 77.2% and 57.5%. Our approach enhances performance across models of varying sizes while generalizing effectively across domains. Further analysis reveals that HiAR-ICL can also serve as a plug-and-play inference method compatible with post-training techniques like GRPO. Code and data are available at https://github.com/jinyangwu/HiARICL.
