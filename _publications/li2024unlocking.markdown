---
layout: publication
title: 'Unlocking Large Language Model''s Planning Capabilities With Maximum Diversity Fine-tuning'
authors: Li Wenjun, Chen Changyu, Varakantham Pradeep
conference: "Arxiv"
year: 2024
bibkey: li2024unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10479"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) have demonstrated impressive task-solving capabilities, achieved through either prompting techniques or system designs. However, concerns have arisen regarding their proficiency in planning tasks, as they often struggle to generate valid plans. This paper investigates the impact of fine-tuning on LLMs' planning capabilities. Our findings indicate that LLMs can achieve good performance in planning through substantial (thousands of specific examples) fine-tuning. However, fine-tuning is associated with significant economic and computational costs. To address this challenge, we propose the Maximum Diversity Fine-Tuning (MDFT) strategy to improve the sample efficiency of fine-tuning in the planning domain. Specifically, our algorithm, referred to as MDFT-g, encodes the planning task instances with their graph representations and selects a subset of samples in the vector space that maximizes data diversity. We empirically demonstrate that MDFT-g consistently outperforms existing baselines at various scales across multiple benchmark domains.
