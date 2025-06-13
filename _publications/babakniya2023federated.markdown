---
layout: publication
title: 'Slora: Federated Parameter Efficient Fine-tuning Of Language Models'
authors: Sara Babakniya, Ahmed Roushdy Elkordy, Yahya H. Ezzeldin, Qingfeng Liu, Kee-bong Song, Mostafa El-khamy, Salman Avestimehr
conference: "Arxiv"
year: 2023
bibkey: babakniya2023federated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.06522"}
tags: ['Fine-Tuning', 'Transformer', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Transfer learning via fine-tuning pre-trained transformer models has gained
significant success in delivering state-of-the-art results across various NLP
tasks. In the absence of centralized data, Federated Learning (FL) can benefit
from distributed and private data of the FL edge clients for fine-tuning.
However, due to the limited communication, computation, and storage
capabilities of edge devices and the huge sizes of popular transformer models,
efficient fine-tuning is crucial to make federated training feasible. This work
explores the opportunities and challenges associated with applying parameter
efficient fine-tuning (PEFT) methods in different FL settings for language
tasks. Specifically, our investigation reveals that as the data across users
becomes more diverse, the gap between fully fine-tuning the model and employing
PEFT methods widens. To bridge this performance gap, we propose a method called
SLoRA, which overcomes the key limitations of LoRA in high heterogeneous data
scenarios through a novel data-driven initialization technique. Our
experimental results demonstrate that SLoRA achieves performance comparable to
full fine-tuning, with significant sparse updates with approximately \\(\sim 1%\\)
density while reducing training time by up to \\(90%\\).
