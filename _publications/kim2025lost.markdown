---
layout: publication
title: 'Lost In Sequence: Do Large Language Models Understand Sequential Recommendation?'
authors: Sein Kim, Hongseok Kang, Kibum Kim, Jiwan Kim, Donghyun Kim, Minchul Yang, Kwangjin Oh, Julian Mcauley, Chanyoung Park
conference: "Arxiv"
year: 2025
bibkey: kim2025lost
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13909'}
  - {name: "Code", url: 'https://github.com/Sein-Kim/LLM-SRec'}
tags: ['Has Code', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) have recently emerged as promising tools for
recommendation thanks to their advanced textual understanding ability and
context-awareness. Despite the current practice of training and evaluating
LLM-based recommendation (LLM4Rec) models under a sequential recommendation
scenario, we found that whether these models understand the sequential
information inherent in users' item interaction sequences has been largely
overlooked. In this paper, we first demonstrate through a series of experiments
that existing LLM4Rec models do not fully capture sequential information both
during training and inference. Then, we propose a simple yet effective
LLM-based sequential recommender, called LLM-SRec, a method that enhances the
integration of sequential information into LLMs by distilling the user
representations extracted from a pre-trained CF-SRec model into LLMs. Our
extensive experiments show that LLM-SRec enhances LLMs' ability to understand
users' item interaction sequences, ultimately leading to improved
recommendation performance. Furthermore, unlike existing LLM4Rec models that
require fine-tuning of LLMs, LLM-SRec achieves state-of-the-art performance by
training only a few lightweight MLPs, highlighting its practicality in
real-world applications. Our code is available at
https://github.com/Sein-Kim/LLM-SRec.
