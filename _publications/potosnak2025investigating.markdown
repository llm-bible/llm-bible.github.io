---
layout: publication
title: 'Investigating Compositional Reasoning In Time Series Foundation Models'
authors: Willa Potosnak, Cristian Challu, Mononito Goswami, Kin G. Olivares, Michał Wiliński, Nina Żukowska, Artur Dubrawski
conference: "Arxiv"
year: 2025
bibkey: potosnak2025investigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06037'}
tags: ['Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Tokenization', 'Pretraining Methods']
---
Large pre-trained time series foundation models (TSFMs) have demonstrated
promising zero-shot performance across a wide range of domains. However, a
question remains: Do TSFMs succeed solely by memorizing training patterns, or
do they possess the ability to reason? While reasoning is a topic of great
interest in the study of Large Language Models (LLMs), it is undefined and
largely unexplored in the context of TSFMs. In this work, inspired by language
modeling literature, we formally define compositional reasoning in forecasting
and distinguish it from in-distribution generalization. We evaluate the
reasoning and generalization capabilities of 23 popular deep learning
forecasting models on multiple synthetic and real-world datasets. Additionally,
through controlled studies, we systematically examine which design choices in
TSFMs contribute to improved reasoning abilities. Our study yields key insights
into the impact of TSFM architecture design on compositional reasoning and
generalization. We find that patch-based Transformers have the best reasoning
performance, closely followed by residualized MLP-based architectures, which
are 97% less computationally complex in terms of FLOPs and 86% smaller in
terms of the number of trainable parameters. Interestingly, in some zero-shot
out-of-distribution scenarios, these models can outperform moving average and
exponential smoothing statistical baselines trained on in-distribution data.
Only a few design choices, such as the tokenization method, had a significant
(negative) impact on Transformer model performance.
