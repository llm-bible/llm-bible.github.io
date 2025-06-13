---
layout: publication
title: 'Following The Whispers Of Values: Unraveling Neural Mechanisms Behind Value-oriented Behaviors In Llms'
authors: Ling Hu, Yuemei Xu, Xiaoyang Gu, Letao Han
conference: "Arxiv"
year: 2025
bibkey: hu2025following
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.04994'}
tags: ['Interpretability and Explainability', 'RAG', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias', 'Responsible AI']
---
Despite the impressive performance of large language models (LLMs), they can
present unintended biases and harmful behaviors driven by encoded values,
emphasizing the urgent need to understand the value mechanisms behind them.
However, current research primarily evaluates these values through external
responses with a focus on AI safety, lacking interpretability and failing to
assess social values in real-world contexts. In this paper, we propose a novel
framework called ValueExploration, which aims to explore the behavior-driven
mechanisms of National Social Values within LLMs at the neuron level. As a case
study, we focus on Chinese Social Values and first construct C-voice, a
large-scale bilingual benchmark for identifying and evaluating Chinese Social
Values in LLMs. By leveraging C-voice, we then identify and locate the neurons
responsible for encoding these values according to activation difference.
Finally, by deactivating these neurons, we analyze shifts in model behavior,
uncovering the internal mechanism by which values influence LLM
decision-making. Extensive experiments on four representative LLMs validate the
efficacy of our framework. The benchmark and code will be available.
