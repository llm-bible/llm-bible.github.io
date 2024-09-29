---
layout: publication
title: Dr.icl Demonstration45;retrieved In45;context Learning
authors: Luo Man, Xu Xin, Dai Zhuyun, Pasupat Panupong, Kazemi Mehran, Baral Chitta, Imbrasaite Vaiva, Zhao Vincent Y
conference: "Arxiv"
year: 2023
bibkey: luo2023demonstration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14128"}
tags: ['Prompting', 'Reinforcement Learning', 'Training Techniques']
---
In45;context learning (ICL) teaching a large language model (LLM) to perform a task with few45;shot demonstrations rather than adjusting the model parameters has emerged as a strong paradigm for using LLMs. While early studies primarily used a fixed or random set of demonstrations for all test queries recent research suggests that retrieving semantically similar demonstrations to the input from a pool of available demonstrations results in better performance. This work expands the applicability of retrieval45;based ICL approaches by demonstrating that even simple word45;overlap similarity measures such as BM25 outperform randomly selected demonstrations. Furthermore we extend the success of retrieval45;based ICL to instruction45;finetuned LLMs as well as Chain45;of45;Thought (CoT) prompting. For instruction45;finetuned LLMs we find that although a model has already seen the training data at training time retrieving demonstrations from the training data at test time yields better results compared to using no demonstrations or random demonstrations. Last but not least we train a task45;specific demonstration retriever that outperforms off45;the45;shelf retrievers.
