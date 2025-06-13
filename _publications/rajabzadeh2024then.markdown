---
layout: publication
title: 'Echoatt: Attend, Copy, Then Adjust For More Efficient Large Language Models'
authors: Hossein Rajabzadeh, Aref Jafari, Aman Sharma, Benyamin Jami, Hyock Ju Kwon, Ali Ghodsi, Boxing Chen, Mehdi Rezagholizadeh
conference: "Arxiv"
year: 2024
bibkey: rajabzadeh2024then
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14595'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Tools', 'Model Architecture', 'Applications', 'Fine-Tuning', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs), with their increasing depth and number of
parameters, have demonstrated outstanding performance across a variety of
natural language processing tasks. However, this growth in scale leads to
increased computational demands, particularly during inference and fine-tuning.
To address these challenges, we introduce EchoAtt, a novel framework aimed at
optimizing transformer-based models by analyzing and leveraging the similarity
of attention patterns across layers. Our analysis reveals that many inner
layers in LLMs, especially larger ones, exhibit highly similar attention
matrices. By exploiting this similarity, EchoAtt enables the sharing of
attention matrices in less critical layers, significantly reducing
computational requirements without compromising performance. We incorporate
this approach within a knowledge distillation setup, where a pre-trained
teacher model guides the training of a smaller student model. The student model
selectively shares attention matrices in layers with high similarity while
inheriting key parameters from the teacher. Our best results with
TinyLLaMA-1.1B demonstrate that EchoAtt improves inference speed by 15%,
training speed by 25%, and reduces the number of parameters by approximately
4%, all while improving zero-shot performance. These findings highlight the
potential of attention matrix sharing to enhance the efficiency of LLMs, making
them more practical for real-time and resource-limited applications.
