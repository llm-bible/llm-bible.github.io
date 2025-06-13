---
layout: publication
title: 'Naive Bayes-based Context Extension For Large Language Models'
authors: Jianlin Su, Murtadha Ahmed, Wenbo, Luo Ao, Mingren Zhu, Yunfeng Liu
conference: "Arxiv"
year: 2024
bibkey: su2024naive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17552"}
  - {name: "Code", url: "https://github.com/amurtadha/NBCE-master"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) have shown promising in-context learning
abilities. However, conventional In-Context Learning (ICL) approaches are often
impeded by length limitations of transformer architecture, which pose
challenges when attempting to effectively integrate supervision from a
substantial number of demonstration examples. In this paper, we introduce a
novel framework, called Naive Bayes-based Context Extension (NBCE), to enable
existing LLMs to perform ICL with an increased number of demonstrations by
significantly expanding their context size. Importantly, this expansion does
not require fine-tuning or dependence on particular model architectures, all
the while preserving linear efficiency. NBCE initially splits the context into
equal-sized windows fitting the target LLM's maximum length. Then, it
introduces a voting mechanism to select the most relevant window, regarded as
the posterior context. Finally, it employs Bayes' theorem to generate the test
task. Our experimental results demonstrate that NBCE substantially enhances
performance, particularly as the number of demonstration examples increases,
consistently outperforming alternative methods. The NBCE code will be made
publicly accessible. The code NBCE is available at:
https://github.com/amurtadha/NBCE-master
