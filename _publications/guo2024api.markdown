---
layout: publication
title: 'API Pack: A Massive Multi-programming Language Dataset For API Call Generation'
authors: Guo Zhen, Soria Adriana Meza, Sun Wei, Shen Yikang, Panda Rameswar
conference: "Arxiv"
year: 2024
bibkey: guo2024api
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09615"}
  - {name: "Code", url: "https://github.com/zguo0525/API-Pack"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
We introduce API Pack, a massive multi-programming language dataset
containing more than 1 million instruction-API call pairs to improve the API
call generation capabilities of large language models. By fine-tuning
CodeLlama-13B on 20,000 Python instances from API Pack, we enable it to
outperform GPT-3.5 and GPT-4 in generating unseen API calls. Fine-tuning on API
Pack also facilitates cross-programming language generalization by leveraging a
large amount of data in one language and small amounts of data from other
languages. Scaling the training data to 1 million instances further improves
the model's ability to generalize to new APIs not used in training. To
facilitate further research, we open-source the API Pack dataset, trained
model, and associated source code at https://github.com/zguo0525/API-Pack.
