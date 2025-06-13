---
layout: publication
title: 'Selfelicit: Your Language Model Secretly Knows Where Is The Relevant Evidence'
authors: Zhining Liu, Rana Ali Amjad, Ravinarayana Adkathimar, Tianxin Wei, Hanghang Tong
conference: "Arxiv"
year: 2025
bibkey: liu2025your
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.08767'}
  - {name: "Code", url: 'https://github.com/ZhiningLiu1998/SelfElicit'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Providing Language Models (LMs) with relevant evidence in the context (either via retrieval or user-provided) can significantly improve their ability to provide better-grounded responses. However, recent studies have found that LMs often struggle to fully comprehend and utilize key evidence from the context, especially when it contains noise and irrelevant information, an issue common in real-world scenarios. To address this, we propose SelfElicit, an inference-time approach that helps LMs focus on key contextual evidence through self-guided explicit highlighting. By leveraging the inherent evidence-finding capabilities of LMs using the attention scores of deeper layers, our method automatically identifies and emphasizes key evidence within the input context, facilitating more accurate and grounded responses without additional training or iterative prompting. We demonstrate that SelfElicit brings consistent and significant improvement on multiple evidence-based QA tasks for various LM families while maintaining computational efficiency. Our code and documentation are available at https://github.com/ZhiningLiu1998/SelfElicit.
