---
layout: publication
title: 'An Empirical Study Of Catastrophic Forgetting In Large Language Models During Continual Fine-tuning'
authors: Luo Yun, Yang Zhen, Meng Fandong, Li Yafu, Zhou Jie, Zhang Yue
conference: "Arxiv"
year: 2023
bibkey: luo2023empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.08747"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Catastrophic forgetting (CF) is a phenomenon that occurs in machine learning when a model forgets previously learned information while acquiring new knowledge. As large language models (LLMs) have demonstrated remarkable performance, it is intriguing to investigate whether CF exists during the continual instruction tuning of LLMs. This study empirically evaluates the forgetting phenomenon in LLMs' knowledge during continual instruction tuning from the perspectives of domain knowledge, reasoning, and reading comprehension. The experiments reveal that catastrophic forgetting is generally observed in LLMs ranging from 1b to 7b parameters. Moreover, as the model scale increases, the severity of forgetting intensifies. Comparing the decoder-only model BLOOMZ with the encoder-decoder model mT0, BLOOMZ exhibits less forgetting and retains more knowledge. Interestingly, we also observe that LLMs can mitigate language biases, such as gender bias, during continual fine-tuning. Furthermore, our findings indicate that ALPACA maintains more knowledge and capacity compared to LLAMA during continual fine-tuning, suggesting that general instruction tuning can help alleviate the forgetting phenomenon in LLMs during subsequent fine-tuning processes.
