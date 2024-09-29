---
layout: publication
title: Contrastive Learning For Prompt45;based Few45;shot Language Learners
authors: Jian Yiren, Gao Chongyang, Vosoughi Soroush
conference: "Arxiv"
year: 2022
bibkey: jian2022contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.01308"}
  - {name: "Code", url: "https://github.com/yiren&#45;jian/LM&#45;SupCon"}
tags: ['BERT', 'GPT', 'Has Code', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools']
---
The impressive performance of GPT45;3 using natural language prompts and in45;context learning has inspired work on better fine45;tuning of moderately45;sized models under this paradigm. Following this line of work we present a contrastive learning framework that clusters inputs from the same class for better generality of models trained with only limited examples. Specifically we propose a supervised contrastive framework that clusters inputs from the same class under different augmented views and repel the ones from different classes. We create different views of an example by appending it with different language prompts and contextual demonstrations. Combining a contrastive loss with the standard masked language modeling (MLM) loss in prompt45;based few45;shot learners the experimental results show that our method can improve over the state45;of45;the45;art methods in a diverse set of 15 language tasks. Our framework makes minimal assumptions on the task or the base model and can be applied to many recent methods with little modification. The code will be made available at https://github.com/yiren&#45;jian/LM&#45;SupCon.
