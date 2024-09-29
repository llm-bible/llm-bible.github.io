---
layout: publication
title: TAT-LLM A Specialized Language Model For Discrete Reasoning Over Tabular And Textual Data
authors: Zhu Fengbin, Liu Ziyang, Feng Fuli, Wang Chao, Li Moxin, Chua Tat-seng
conference: "Arxiv"
year: 2024
bibkey: zhu2024tat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13223"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Security', 'Training Techniques']
---
In this work we address question answering (QA) over a hybrid of tabular and textual data that are very common content on the Web (e.g. SEC filings) where discrete reasoning capabilities are often required. Recently large language models (LLMs) like GPT-4 have demonstrated strong multi-step reasoning capabilities. We then consider harnessing the amazing power of LLMs to solve our task. We abstract a Step-wise Pipeline for tabular and textual QA which consists of three key steps including Extractor Reasoner and Executor and initially design an instruction to instantiate the pipeline and validate that GPT-4 outperforms all existing methods. However utilizing an online LLM like GPT-4 holds various challenges in terms of cost latency and data security risk which motivates us to specialize smaller LLMs in this task. We develop a TAT-LLM language model by fine-tuning LLaMA 2 with the training data generated automatically from existing expert-annotated datasets following the Step-wise Pipeline. The experimental results have verified that our TAT-LLM model can outperform all baseline models including the previous best fine-tuned models and very large-scale LLMs like GPT-4 on FinQA TAT-QA and TAT-DQA benchmarks.
