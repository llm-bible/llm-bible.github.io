---
layout: publication
title: 'Are We Falling In A Middle-intelligence Trap? An Analysis And Mitigation Of The Reversal Curse'
authors: Lv Ang, Zhang Kaiyi, Xie Shufang, Tu Quan, Chen Yuhan, Wen Ji-rong, Yan Rui
conference: "Arxiv"
year: 2023
bibkey: lv2023are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.07468"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Recent studies have highlighted a phenomenon in large language models (LLMs) known as the reversal curse in which the order of knowledge entities in the training data biases the models comprehension. For example if a model is trained on sentences where entity A consistently appears before entity B it can respond to queries about A by providing B as the answer. However it may encounter confusion when presented with questions concerning B. We contend that the reversal curse is partially a result of specific model training objectives particularly evident in the prevalent use of the next-token prediction within most causal language models. For the next-token prediction models solely focus on a tokens preceding context resulting in a restricted comprehension of the input. In contrast we illustrate that the GLM trained using the autoregressive blank infilling objective where tokens to be predicted have access to the entire context exhibits better resilience against the reversal curse. We propose a novel training method BIdirectional Casual language modeling Optimization (BICO) designed to mitigate the reversal curse when fine-tuning pretrained causal language models on new data. BICO modifies the causal attention mechanism to function bidirectionally and employs a mask denoising optimization. In the task designed to assess the reversal curse our approach improves Llamas accuracy from the original 037; to around 7037;. We hope that more attention can be focused on exploring and addressing these inherent weaknesses of the current LLMs in order to achieve a higher level of intelligence.
