---
layout: publication
title: 'Cost-effective Hyperparameter Optimization For Large Language Model Generation Inference'
authors: Wang Chi, Liu Susan Xueqing, Awadallah Ahmed H.
conference: "Arxiv"
year: 2023
bibkey: wang2023cost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.04673"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Language Modeling', 'Model Architecture', 'Pruning', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have sparked significant interest in their
generative capabilities, leading to the development of various commercial
applications. The high cost of using the models drives application builders to
maximize the value of generation under a limited inference budget. This paper
presents a study of optimizing inference hyperparameters such as the number of
responses, temperature and max tokens, which significantly affects the
utility/cost of text generation. We design a framework named EcoOptiGen which
leverages economical hyperparameter optimization and cost-based pruning.
Experiments with the GPT-3.5/GPT-4 models on a variety of tasks verify its
effectiveness. EcoOptiGen is implemented in the `autogen' package of the FLAML
library: \url\{https://aka.ms/autogen\}.
