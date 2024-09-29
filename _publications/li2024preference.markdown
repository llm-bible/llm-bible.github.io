---
layout: publication
title: Preference Tuning For Toxicity Mitigation Generalizes Across Languages
authors: Li Xiaochen, Yong Zheng-xin, Bach Stephen H.
conference: "Arxiv"
year: 2024
bibkey: li2024preference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16235"}
tags: ['Efficiency And Optimization', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Reinforcement Learning', 'Responsible AI', 'Tools', 'Training Techniques']
---
Detoxifying multilingual Large Language Models (LLMs) has become crucial due to their increasing global use. In this work we explore zero45;shot cross45;lingual generalization of preference tuning in detoxifying LLMs. Unlike previous studies that show limited cross45;lingual generalization for other safety tasks we demonstrate that Direct Preference Optimization (DPO) training with only English data can significantly reduce toxicity in multilingual open45;ended generations. For example the probability of mGPT45;1.3B generating toxic continuations drops from 46.837; to 3.937; across 17 different languages after training. Our results also extend to other multilingual LLMs such as BLOOM Llama3 and Aya45;23. Using mechanistic interpretability tools like causal intervention and activation analysis we identified the dual multilinguality property of MLP layers in LLMs which explains the cross45;lingual generalization of DPO. Finally we show that bilingual sentence retrieval can predict the cross45;lingual transferability of DPO preference tuning.
