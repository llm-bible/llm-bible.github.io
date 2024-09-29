---
layout: publication
title: 'Table-gpt: Table-tuned GPT For Diverse Table Tasks'
authors: Li Peng, He Yeye, Yashar Dror, Cui Weiwei, Ge Song, Zhang Haidong, Fainman Danielle Rifinski, Zhang Dongmei, Chaudhuri Surajit
conference: "Arxiv"
year: 2023
bibkey: li2023table
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09263"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Language models such as GPT-3.5 and ChatGPT demonstrate remarkable abilities to follow diverse human instructions and perform a wide range of tasks. However when probing language models using a range of basic table-understanding tasks we observe that todays language models are still sub-optimal in many table-related tasks likely because they are pre-trained predominantly on (emphone-dimensional) natural-language texts whereas relational tables are (emphtwo-dimensional) objects. In this work we propose a new (emphtable-tuning) paradigm where we continue to train/fine-tune language models like GPT-3.5 and ChatGPT using diverse table-tasks synthesized from real tables as training data with the goal of enhancing language models ability to understand tables and perform table tasks. We show that our resulting Table-GPT models demonstrate (1) better (emphtable-understanding) capabilities by consistently outperforming the vanilla GPT-3.5 and ChatGPT on a wide-range of table tasks including holdout unseen tasks and (2) strong (emphgeneralizability) in its ability to respond to diverse human instructions to perform new table-tasks in a manner similar to GPT-3.5 and ChatGPT.
