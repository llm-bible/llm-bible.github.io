---
layout: publication
title: TAT45;LLM A Specialized Language Model For Discrete Reasoning Over Tabular And Textual Data
authors: Zhu Fengbin, Liu Ziyang, Feng Fuli, Wang Chao, Li Moxin, Chua Tat-seng
conference: "Arxiv"
year: 2024
bibkey: zhu2024tat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13223"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Security', 'Training Techniques']
---
In this work we address question answering (QA) over a hybrid of tabular and textual data that are very common content on the Web (e.g. SEC filings) where discrete reasoning capabilities are often required. Recently large language models (LLMs) like GPT45;4 have demonstrated strong multi45;step reasoning capabilities. We then consider harnessing the amazing power of LLMs to solve our task. We abstract a Step45;wise Pipeline for tabular and textual QA which consists of three key steps including Extractor Reasoner and Executor and initially design an instruction to instantiate the pipeline and validate that GPT45;4 outperforms all existing methods. However utilizing an online LLM like GPT45;4 holds various challenges in terms of cost latency and data security risk which motivates us to specialize smaller LLMs in this task. We develop a TAT45;LLM language model by fine45;tuning LLaMA 2 with the training data generated automatically from existing expert45;annotated datasets following the Step45;wise Pipeline. The experimental results have verified that our TAT45;LLM model can outperform all baseline models including the previous best fine45;tuned models and very large45;scale LLMs like GPT45;4 on FinQA TAT45;QA and TAT45;DQA benchmarks.
