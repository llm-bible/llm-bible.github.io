---
layout: publication
title: 'Efficient Large Scale Language Modeling With Mixtures Of Experts'
authors: Artetxe Mikel, Bhosale Shruti, Goyal Naman, Mihaylov Todor, Ott Myle, Shleifer Sam, Lin Xi Victoria, Du Jingfei, Iyer Srinivasan, Pasunuru Ramakanth, Anantharaman Giri, Li Xian, Chen Shuohui, Akin Halil, Baines Mandeep, Martin Louis, Zhou Xing, Koura Punit Singh, O'horo Brian, Wang Jeff, Zettlemoyer Luke, Diab Mona, Kozareva Zornitsa, Stoyanov Ves
conference: "Arxiv"
year: 2021
bibkey: artetxe2021efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.10684"}
tags: ['Few Shot', 'Fine Tuning', 'GPT', 'Language Modeling', 'Pretraining Methods', 'Training Techniques']
---
Mixture of Experts layers (MoEs) enable efficient scaling of language models through conditional computation. This paper presents a detailed empirical study of how autoregressive MoE language models scale in comparison with dense models in a wide range of settings: in- and out-of-domain language modeling, zero- and few-shot priming, and full-shot fine-tuning. With the exception of fine-tuning, we find MoEs to be substantially more compute efficient. At more modest training budgets, MoEs can match the performance of dense models using \\(\sim\\)4 times less compute. This gap narrows at scale, but our largest MoE model (1.1T parameters) consistently outperforms a compute-equivalent dense model (6.7B parameters). Overall, this performance gap varies greatly across tasks and domains, suggesting that MoE and dense models generalize differently in ways that are worthy of future study. We make our code and models publicly available for research use.
