---
layout: publication
title: Numllm&#58; Numeric-sensitive Large Language Model For Chinese Finance
authors: Su Huan-yi, Wu Ke, Huang Yu-hao, Li Wu-jun
conference: "Arxiv"
year: 2024
bibkey: su2024numeric
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00566"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Recently many works have proposed various financial large language models (FinLLMs) by pre-training from scratch or fine-tuning open-sourced LLMs on financial corpora. However existing FinLLMs exhibit unsatisfactory performance in understanding financial text when numeric variables are involved in questions. In this paper we propose a novel LLM called numeric-sensitive large language model (NumLLM) for Chinese finance. We first construct a financial corpus from financial textbooks which is essential for improving numeric capability of LLMs during fine-tuning. After that we train two individual low-rank adaptation (LoRA) modules by fine-tuning on our constructed financial corpus. One module is for adapting general-purpose LLMs to financial domain and the other module is for enhancing the ability of NumLLM to understand financial text with numeric variables. Lastly we merge the two LoRA modules into the foundation model to obtain NumLLM for inference. Experiments on financial question-answering benchmark show that NumLLM can boost the performance of the foundation model and can achieve the best overall performance compared to all baselines on both numeric and non-numeric questions.
