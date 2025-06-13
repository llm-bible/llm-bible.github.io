---
layout: publication
title: 'API Pack: A Massive Multi-programming Language Dataset For API Call Generation'
authors: Zhen Guo, Adriana Meza Soria, Wei Sun, Yikang Shen, Rameswar Panda
conference: "Arxiv"
year: 2024
bibkey: guo2024api
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09615"}
  - {name: "Code", url: "https://github.com/zguo0525/API-Pack"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
We introduce API Pack, a massive multi-programming language dataset
containing over one million instruction-API calls for improving the API call
generation capabilities of large language models. Our evaluation highlights
three key findings: First, fine-tuning on API Pack enables open-source models
to outperform GPT-3.5 and GPT-4 in generating code for entirely new API calls.
We show this by fine-tuning CodeLlama-13B on 20,000 Python instances from API
Pack. Second, fine-tuning on a large dataset in one language, combined with
smaller datasets from others, improves API generation accuracy across multiple
languages. Third, we confirm the benefits of larger datasets for API
generalization, as increasing fine-tuning data to one million instances
enhances generalization to new APIs. To support further research, we
open-source the API Pack dataset, trained model, and code at
https://github.com/zguo0525/API-Pack.
