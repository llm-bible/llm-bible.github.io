---
layout: publication
title: Numllm Numeric45;sensitive Large Language Model For Chinese Finance
authors: Su Huan-yi, Wu Ke, Huang Yu-hao, Li Wu-jun
conference: "Arxiv"
year: 2024
bibkey: su2024numeric
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00566"}
tags: ['Applications', 'Fine Tuning', 'Training Techniques']
---
Recently many works have proposed various financial large language models (FinLLMs) by pre45;training from scratch or fine45;tuning open45;sourced LLMs on financial corpora. However existing FinLLMs exhibit unsatisfactory performance in understanding financial text when numeric variables are involved in questions. In this paper we propose a novel LLM called numeric45;sensitive large language model (NumLLM) for Chinese finance. We first construct a financial corpus from financial textbooks which is essential for improving numeric capability of LLMs during fine45;tuning. After that we train two individual low45;rank adaptation (LoRA) modules by fine45;tuning on our constructed financial corpus. One module is for adapting general45;purpose LLMs to financial domain and the other module is for enhancing the ability of NumLLM to understand financial text with numeric variables. Lastly we merge the two LoRA modules into the foundation model to obtain NumLLM for inference. Experiments on financial question45;answering benchmark show that NumLLM can boost the performance of the foundation model and can achieve the best overall performance compared to all baselines on both numeric and non45;numeric questions.
