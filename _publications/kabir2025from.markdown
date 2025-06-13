---
layout: publication
title: 'From N-gram To Attention: How Model Architectures Learn And Propagate Bias In Language Modeling'
authors: Mohsinul Kabir, Tasfia Tahsin, Sophia Ananiadou
conference: "Arxiv"
year: 2025
bibkey: kabir2025from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12381"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'Ethics and Bias', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Current research on bias in language models (LMs) predominantly focuses on data quality, with significantly less attention paid to model architecture and temporal influences of data. Even more critically, few studies systematically investigate the origins of bias. We propose a methodology grounded in comparative behavioral theory to interpret the complex interaction between training data and model architecture in bias propagation during language modeling. Building on recent work that relates transformers to n-gram LMs, we evaluate how data, model design choices, and temporal dynamics affect bias propagation. Our findings reveal that: (1) n-gram LMs are highly sensitive to context window size in bias propagation, while transformers demonstrate architectural robustness; (2) the temporal provenance of training data significantly affects bias; and (3) different model architectures respond differentially to controlled bias injection, with certain biases (e.g. sexual orientation) being disproportionately amplified. As language models become ubiquitous, our findings highlight the need for a holistic approach -- tracing bias to its origins across both data and model dimensions, not just symptoms, to mitigate harm.
