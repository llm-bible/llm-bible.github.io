---
layout: publication
title: Context45;aware Meta45;learning
authors: Fifty Christopher, Duan Dennis, Junkins Ronald G., Amid Ehsan, Leskovec Jure, Re Christopher, Thrun Sebastian
conference: "Arxiv"
year: 2023
bibkey: fifty2023context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10971"}
  - {name: "Code", url: "https://github.com/cfifty/CAML"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models like ChatGPT demonstrate a remarkable capacity to learn new concepts during inference without any fine45;tuning. However visual models trained to detect new objects during inference have been unable to replicate this ability and instead either perform poorly or require meta45;training and/or fine45;tuning on similar objects. In this work we propose a meta45;learning algorithm that emulates Large Language Models by learning new visual concepts during inference without fine45;tuning. Our approach leverages a frozen pre45;trained feature extractor and analogous to in45;context learning recasts visual meta45;learning as sequence modeling over datapoints with known labels and a test datapoint with an unknown label. On 8 out of 11 meta45;learning benchmarks our approach 45;45; without meta45;training or fine45;tuning 45;45; exceeds or matches the state45;of45;the45;art algorithm PMF which is meta45;trained on these benchmarks. Our code is available at https://github.com/cfifty/CAML.
