---
layout: publication
title: Context-Aware Meta-Learning
authors: Fifty Christopher, Duan Dennis, Junkins Ronald G., Amid Ehsan, Leskovec Jure, Re Christopher, Thrun Sebastian
conference: "Arxiv"
year: 2023
bibkey: fifty2023context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10971"}
  - {name: "Code", url: "https://github.com/cfifty/CAML"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models like ChatGPT demonstrate a remarkable capacity to learn new concepts during inference without any fine-tuning. However visual models trained to detect new objects during inference have been unable to replicate this ability and instead either perform poorly or require meta-training and/or fine-tuning on similar objects. In this work we propose a meta-learning algorithm that emulates Large Language Models by learning new visual concepts during inference without fine-tuning. Our approach leverages a frozen pre-trained feature extractor and analogous to in-context learning recasts visual meta-learning as sequence modeling over datapoints with known labels and a test datapoint with an unknown label. On 8 out of 11 meta-learning benchmarks our approach -- without meta-training or fine-tuning -- exceeds or matches the state-of-the-art algorithm PMF which is meta-trained on these benchmarks. Our code is available at https://github.com/cfifty/CAML.
