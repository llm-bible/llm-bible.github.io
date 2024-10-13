---
layout: publication
title: 'Improving Small Language Models On Pubmedqa Via Generative Data Augmentation'
authors: Guo Zhen, Wang Peiqi, Wang Yanwei, Yu Shangdi
conference: "Arxiv"
year: 2023
bibkey: guo2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.07804"}
tags: ['Applications', 'Efficiency And Optimization', 'Few Shot', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Large Language Models (LLMs) have made remarkable advancements in the field
of natural language processing. However, their increasing size poses challenges
in terms of computational cost. On the other hand, Small Language Models (SLMs)
are known for their efficiency, but they often struggle with limited capacity
and training data, especially in specific domains. In this paper, we introduce
a novel method aimed at improving SLMs in the medical domain using LLM-based
generative data augmentation. The objective of our approach is to develop more
efficient and capable models that are specifically tailored for specialized
applications. Through experiments conducted on the PubMedQA dataset, we
demonstrate the effectiveness of LLMs in refining and diversifying existing
question-answer pairs. This refinement process leads to improved performance in
a significantly smaller model after fine-tuning. Notably, our best SLM, with
under 1.6 billion parameters, outperforms the few-shot GPT-4 on the PubMedQA
dataset. Our code and generated data are publicly available to facilitate
further explorations.
