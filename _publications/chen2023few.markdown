---
layout: publication
title: Few45;shot Data Synthesis For Open Domain Multi45;hop Question Answering
authors: Chen Mingda, Chen Xilun, Yih Wen-tau
conference: "Arxiv"
year: 2023
bibkey: chen2023few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13691"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Tools']
---
Few45;shot learning for open domain multi45;hop question answering typically relies on the incontext learning capability of large language models (LLMs). While powerful these LLMs usually contain tens or hundreds of billions of parameters making them rather inefficient at inference time. To improve performance of smaller language models we propose a data synthesis framework for multi45;hop question answering that requires less than 10 human annotated question answer pairs. Our framework depends only on rich naturally45;occurring relationships among documents and is built upon the data generation functions parameterized by LLMs and prompts. We synthesize millions of multi45;hop questions and claims to finetune language models evaluated on popular benchmarks for multi45;hop question answering and fact verification. Empirically our approach improves model performance significantly allowing the finetuned models to be competitive with GPT45;3.5 based approaches while being almost one45;third the size in parameter count.
