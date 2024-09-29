---
layout: publication
title: Axformer Accuracy45;driven Approximation Of Transformers For Faster Smaller And More Accurate NLP Models
authors: Nagarajan Amrit, Sen Sanchari, Stevens Jacob R., Raghunathan Anand
conference: "Arxiv"
year: 2020
bibkey: nagarajan2020accuracy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.03688"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'RAG', 'Tools', 'Transformer']
---
Transformers have greatly advanced the state45;of45;the45;art in Natural Language Processing (NLP) in recent years but present very large computation and storage requirements. We observe that the design process of Transformers (pre45;train a foundation model on a large dataset in a self45;supervised manner and subsequently fine45;tune it for different downstream tasks) leads to task45;specific models that are highly over45;parameterized adversely impacting both accuracy and inference efficiency. We propose AxFormer a systematic framework that applies accuracy45;driven approximations to create optimized transformer models for a given downstream task. AxFormer combines two key optimizations 45;45; accuracy45;driven pruning and selective hard attention. Accuracy45;driven pruning identifies and removes parts of the fine45;tuned transformer that hinder performance on the given downstream task. Sparse hard45;attention optimizes attention blocks in selected layers by eliminating irrelevant word aggregations thereby helping the model focus only on the relevant parts of the input. In effect AxFormer leads to models that are more accurate while also being faster and smaller. Our experiments on GLUE and SQUAD tasks show that AxFormer models are up to 4.537; more accurate while also being up to 2.5X faster and up to 3.2X smaller than conventional fine45;tuned models. In addition we demonstrate that AxFormer can be combined with previous efforts such as distillation or quantization to achieve further efficiency gains.
