---
layout: publication
title: Steering Large Language Models For Machine Translation With Finetuning And In45;context Learning
authors: Alves Duarte M., Guerreiro Nuno M., Alves João, Pombal José, Rei Ricardo, De Souza José G. C., Colombo Pierre, Martins André F. T.
conference: "Arxiv"
year: 2023
bibkey: alves2023steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13448"}
tags: ['Applications', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) are a promising avenue for machine translation (MT). However current LLM45;based MT systems are brittle their effectiveness highly depends on the choice of few45;shot examples and they often require extra post45;processing due to overgeneration. Alternatives such as finetuning on translation instructions are computationally expensive and may weaken in45;context learning capabilities due to overspecialization. In this paper we provide a closer look at this problem. We start by showing that adapter45;based finetuning with LoRA matches the performance of traditional finetuning while reducing the number of training parameters by a factor of 50. This method also outperforms few45;shot prompting and eliminates the need for post45;processing or in45;context examples. However we show that finetuning generally degrades few45;shot performance hindering adaptation capabilities. Finally to obtain the best of both worlds we propose a simple approach that incorporates few45;shot examples during finetuning. Experiments on 10 language pairs show that our proposed approach recovers the original few45;shot capabilities while keeping the added benefits of finetuning.
