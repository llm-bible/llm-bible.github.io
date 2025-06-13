---
layout: publication
title: 'Unleashing LLM Reasoning Capability Via Scalable Question Synthesis From Scratch'
authors: Yuyang Ding, Xinyu Shi, Xiaobo Liang, Juntao Li, Zhaopeng Tu, Qiaoming Zhu, Min Zhang
conference: "Arxiv"
year: 2024
bibkey: ding2024unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18693"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Improving the mathematical reasoning capabilities of Large Language Models (LLMs) is critical for advancing artificial intelligence. However, access to extensive, diverse, and high-quality reasoning datasets remains a significant challenge, particularly for the open-source community. In this paper, we propose ScaleQuest, a novel, scalable, and cost-effective data synthesis method that enables the generation of large-scale mathematical reasoning datasets using lightweight 7B-scale models. ScaleQuest introduces a two-stage question-tuning process comprising Question Fine-Tuning (QFT) and Question Preference Optimization (QPO) to unlock the question generation capabilities of problem-solving models. By generating diverse questions from scratch -- without relying on powerful proprietary models or seed data -- we produce a dataset of 1 million problem-solution pairs. Our experiments demonstrate that models trained on our data outperform existing open-source datasets in both in-domain and out-of-domain evaluations. Furthermore, our approach shows continued performance improvement as the volume of training data increases, highlighting its potential for ongoing data scaling. The extensive improvements observed in code reasoning tasks demonstrate the generalization capabilities of our proposed method. Our work provides the open-source community with a practical solution to enhance the mathematical reasoning abilities of LLMs.
