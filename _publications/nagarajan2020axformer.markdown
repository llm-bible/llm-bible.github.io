---
layout: publication
title: AxFormer Accuracy-driven Approximation of Transformers for Faster Smaller and more Accurate NLP Models
authors: Nagarajan Amrit, Sen Sanchari, Stevens Jacob R., Raghunathan Anand
conference: "Arxiv"
year: 2020
bibkey: nagarajan2020axformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.03688"}
tags: ['ARXIV', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'NLP', 'Pretraining Methods', 'Quantization', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Transformers have greatly advanced the state-of-the-art in Natural Language Processing (NLP) in recent years but present very large computation and storage requirements. We observe that the design process of Transformers (pre-train a foundation model on a large dataset in a self-supervised manner and subsequently fine-tune it for different downstream tasks) leads to task-specific models that are highly over-parameterized adversely impacting both accuracy and inference efficiency. We propose AxFormer a systematic framework that applies accuracy-driven approximations to create optimized transformer models for a given downstream task. AxFormer combines two key optimizations -- accuracy-driven pruning and selective hard attention. Accuracy-driven pruning identifies and removes parts of the fine-tuned transformer that hinder performance on the given downstream task. Sparse hard-attention optimizes attention blocks in selected layers by eliminating irrelevant word aggregations thereby helping the model focus only on the relevant parts of the input. In effect AxFormer leads to models that are more accurate while also being faster and smaller. Our experiments on GLUE and SQUAD tasks show that AxFormer models are up to 4.5 more accurate while also being up to 2.5X faster and up to 3.2X smaller than conventional fine-tuned models. In addition we demonstrate that AxFormer can be combined with previous efforts such as distillation or quantization to achieve further efficiency gains.
