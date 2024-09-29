---
layout: publication
title: On45;policy Fine45;grained Knowledge Feedback For Hallucination Mitigation
authors: Wen Xueru, Lu Xinyu, Guan Xinyan, Lu Yaojie, Lin Hongyu, He Ben, Han Xianpei, Sun Le
conference: "Arxiv"
year: 2024
bibkey: wen2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12221"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Reinforcement Learning', 'Tools']
---
Hallucination occurs when large language models (LLMs) exhibit behavior that deviates from the boundaries of their knowledge during the response generation process. Previous learning45;based methods focus on detecting knowledge boundaries and finetuning models with instance45;level feedback but they suffer from inaccurate signals due to off45;policy data sampling and coarse45;grained feedback. In this paper we introduce textit123;b123;R125;einforcement b123;L125;earning b123;f125;or b123;H125;allucination125; (RLFH) a fine45;grained feedback45;based online reinforcement learning method for hallucination mitigation. Unlike previous learning45;based methods RLFH enables LLMs to explore the boundaries of their internal knowledge and provide on45;policy fine45;grained feedback on these explorations. To construct fine45;grained feedback for learning reliable generation behavior RLFH decomposes the outcomes of large models into atomic facts provides statement45;level evaluation signals and traces back the signals to the tokens of the original responses. Finally RLFH adopts the online reinforcement algorithm with these token45;level rewards to adjust model behavior for hallucination mitigation. For effective on45;policy optimization RLFH also introduces an LLM45;based fact assessment framework to verify the truthfulness and helpfulness of atomic facts without human intervention. Experiments on HotpotQA SQuADv2 and Biography benchmarks demonstrate that RLFH can balance their usage of internal knowledge during the generation process to eliminate the hallucination behavior of LLMs.
