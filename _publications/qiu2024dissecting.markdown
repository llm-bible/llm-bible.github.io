---
layout: publication
title: Dissecting Multiplication In Transformers Insights Into Llms
authors: Qiu Luyu, Li Jianing, Su Chi, Zhang Chen Jason, Chen Lei
conference: "Arxiv"
year: 2024
bibkey: qiu2024dissecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15360"}
tags: ['Applications', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Transformer45;based large language models have achieved remarkable performance across various natural language processing tasks. However they often struggle with seemingly easy tasks like arithmetic despite their vast capabilities. This stark disparity raise humans concerns about their safe and ethical use hinder their widespread adoption.In this paper we focus on a typical arithmetic task integer multiplication to explore and explain the imperfection of transformers in this domain. We provide comprehensive analysis of a vanilla transformer trained to perform n45;digit integer multiplication. Our observations indicate that the model decomposes multiplication task into multiple parallel subtasks sequentially optimizing each subtask for each digit to complete the final multiplication. Based on observation and analysis we infer the reasons of transformers deficiencies in multiplication tasks lies in their difficulty in calculating successive carryovers and caching intermediate results and confirmed this inference through experiments. Guided by these findings we propose improvements to enhance transformers performance on multiplication tasks. These enhancements are validated through rigorous testing and mathematical modeling not only enhance transformers interpretability but also improve its performance e.g. we achieve over 99.937; accuracy on 545;digit integer multiplication with a tiny transformer outperform LLMs GPT45;4. Our method contributes to the broader fields of model understanding and interpretability paving the way for analyzing more complex tasks and Transformer models. This work underscores the importance of explainable AI helping to build trust in large language models and promoting their adoption in critical applications.
