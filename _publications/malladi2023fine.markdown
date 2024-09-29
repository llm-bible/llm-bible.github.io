---
layout: publication
title: Fine45;tuning Language Models With Just Forward Passes
authors: Malladi Sadhika, Gao Tianyu, Nichani Eshaan, Damian Alex, Lee Jason D., Chen Danqi, Arora Sanjeev
conference: "Arxiv"
year: 2023
bibkey: malladi2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17333"}
tags: ['Fine Tuning', 'GPT', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Fine45;tuning language models (LMs) has yielded success on diverse downstream tasks but as LMs grow in size backpropagation requires a prohibitively large amount of memory. Zeroth45;order (ZO) methods can in principle estimate gradients using only two forward passes but are theorized to be catastrophically slow for optimizing large models. In this work we propose a memory45;efficient zerothorder optimizer (MeZO) adapting the classical ZO45;SGD method to operate in45;place thereby fine45;tuning LMs with the same memory footprint as inference. For example with a single A100 80GB GPU MeZO can train a 3045;billion parameter model whereas fine45;tuning with backpropagation can train only a 2.7B LM with the same budget. We conduct comprehensive experiments across model types (masked and autoregressive LMs) model scales (up to 66B) and downstream tasks (classification multiple45;choice and generation). Our results demonstrate that (1) MeZO significantly outperforms in45;context learning and linear probing; (2) MeZO achieves comparable performance to fine45;tuning with backpropagation across multiple tasks with up to 12x memory reduction and up to 2x GPU45;hour reduction in our implementation; (3) MeZO is compatible with both full45;parameter and parameter45;efficient tuning techniques such as LoRA and prefix tuning; (4) MeZO can effectively optimize non45;differentiable objectives (e.g. maximizing accuracy or F1). We support our empirical findings with theoretical insights highlighting how adequate pre45;training and task prompts enable MeZO to fine45;tune huge models despite classical ZO analyses suggesting otherwise.
