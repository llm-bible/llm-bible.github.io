---
layout: publication
title: 'Steering Large Language Models For Machine Translation With Finetuning And In-context Learning'
authors: Duarte M. Alves, Nuno M. Guerreiro, João Alves, José Pombal, Ricardo Rei, José G. C. De Souza, Pierre Colombo, André F. T. Martins
conference: "Arxiv"
year: 2023
bibkey: alves2023steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13448"}
tags: ['Fine-Tuning', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) are a promising avenue for machine translation
(MT). However, current LLM-based MT systems are brittle: their effectiveness
highly depends on the choice of few-shot examples and they often require extra
post-processing due to overgeneration. Alternatives such as finetuning on
translation instructions are computationally expensive and may weaken
in-context learning capabilities, due to overspecialization. In this paper, we
provide a closer look at this problem. We start by showing that adapter-based
finetuning with LoRA matches the performance of traditional finetuning while
reducing the number of training parameters by a factor of 50. This method also
outperforms few-shot prompting and eliminates the need for post-processing or
in-context examples. However, we show that finetuning generally degrades
few-shot performance, hindering adaptation capabilities. Finally, to obtain the
best of both worlds, we propose a simple approach that incorporates few-shot
examples during finetuning. Experiments on 10 language pairs show that our
proposed approach recovers the original few-shot capabilities while keeping the
added benefits of finetuning.
