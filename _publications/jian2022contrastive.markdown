---
layout: publication
title: 'Contrastive Learning For Prompt-based Few-shot Language Learners'
authors: Yiren Jian, Chongyang Gao, Soroush Vosoughi
conference: "Arxiv"
year: 2022
bibkey: jian2022contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.01308"}
  - {name: "Code", url: "https://github.com/yiren-jian/LM-SupCon"}
tags: ['Masked Language Model', 'Training Techniques', 'Model Architecture', 'Few-Shot', 'Tools', 'Language Modeling', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Has Code', 'Prompting', 'In-Context Learning']
---
The impressive performance of GPT-3 using natural language prompts and
in-context learning has inspired work on better fine-tuning of moderately-sized
models under this paradigm. Following this line of work, we present a
contrastive learning framework that clusters inputs from the same class for
better generality of models trained with only limited examples. Specifically,
we propose a supervised contrastive framework that clusters inputs from the
same class under different augmented "views" and repel the ones from different
classes. We create different "views" of an example by appending it with
different language prompts and contextual demonstrations. Combining a
contrastive loss with the standard masked language modeling (MLM) loss in
prompt-based few-shot learners, the experimental results show that our method
can improve over the state-of-the-art methods in a diverse set of 15 language
tasks. Our framework makes minimal assumptions on the task or the base model,
and can be applied to many recent methods with little modification. The code
will be made available at: https://github.com/yiren-jian/LM-SupCon.
