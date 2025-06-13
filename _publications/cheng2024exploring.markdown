---
layout: publication
title: 'Exploring The Robustness Of In-context Learning With Noisy Labels'
authors: Chen Cheng, Xinzhi Yu, Haodong Wen, Jingsong Sun, Guanzhang Yue, Yihao Zhang, Zeming Wei
conference: "Arxiv"
year: 2024
bibkey: cheng2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.18191"}
  - {name: "Code", url: "https://github.com/InezYu0928/in-context-learning"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Has Code', 'Prompting', 'In-Context Learning']
---
Recently, the mysterious In-Context Learning (ICL) ability exhibited by
Transformer architectures, especially in large language models (LLMs), has
sparked significant research interest. However, the resilience of Transformers'
in-context learning capabilities in the presence of noisy samples, prevalent in
both training corpora and prompt demonstrations, remains underexplored. In this
paper, inspired by prior research that studies ICL ability using simple
function classes, we take a closer look at this problem by investigating the
robustness of Transformers against noisy labels. Specifically, we first conduct
a thorough evaluation and analysis of the robustness of Transformers against
noisy labels during in-context learning and show that they exhibit notable
resilience against diverse types of noise in demonstration labels. Furthermore,
we delve deeper into this problem by exploring whether introducing noise into
the training set, akin to a form of data augmentation, enhances such robustness
during inference, and find that such noise can indeed improve the robustness of
ICL. Overall, our fruitful analysis and findings provide a comprehensive
understanding of the resilience of Transformer models against label noises
during ICL and provide valuable insights into the research on Transformers in
natural language processing. Our code is available at
https://github.com/InezYu0928/in-context-learning.
