---
layout: publication
title: 'Ask, And It Shall Be Given: On The Turing Completeness Of Prompting'
authors: Ruizhong Qiu, Zhe Xu, Wenxuan Bao, Hanghang Tong
conference: "Arxiv"
year: 2024
bibkey: qiu2024it
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01992"}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Prompting']
---
Since the success of GPT, large language models (LLMs) have been
revolutionizing machine learning and have initiated the so-called LLM prompting
paradigm. In the era of LLMs, people train a single general-purpose LLM and
provide the LLM with different prompts to perform different tasks. However,
such empirical success largely lacks theoretical understanding. Here, we
present the first theoretical study on the LLM prompting paradigm to the best
of our knowledge. In this work, we show that prompting is in fact
Turing-complete: there exists a finite-size Transformer such that for any
computable function, there exists a corresponding prompt following which the
Transformer computes the function. Furthermore, we show that even though we use
only a single finite-size Transformer, it can still achieve nearly the same
complexity bounds as that of the class of all unbounded-size Transformers.
Overall, our result reveals that prompting can enable a single finite-size
Transformer to be efficiently universal, which establishes a theoretical
underpinning for prompt engineering in practice.
