---
layout: publication
title: 'Modular Prompt Learning Improves Vision-language Models'
authors: Zhenhan Huang, Tejaswini Pedapati, Pin-yu Chen, Jianxi Gao
conference: "Arxiv"
year: 2025
bibkey: huang2025modular
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14125"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Prompting', 'Attention Mechanism']
---
Pre-trained vision-language models are able to interpret visual concepts and
language semantics. Prompt learning, a method of constructing prompts for text
encoders or image encoders, elicits the potentials of pre-trained models and
readily adapts them to new scenarios. Compared to fine-tuning, prompt learning
enables the model to achieve comparable or better performance using fewer
trainable parameters. Besides, prompt learning freezes the pre-trained model
and avoids the catastrophic forgetting issue in the fine-tuning. Continuous
prompts inserted into the input of every transformer layer (i.e. deep prompts)
can improve the performances of pre-trained models on downstream tasks. For
i-th transformer layer, the inserted prompts replace previously inserted
prompts in the \\((i-1)\\)-th layer. Although the self-attention mechanism
contextualizes newly inserted prompts for the current layer and embeddings from
the previous layer's output, removing all inserted prompts from the previous
layer inevitably loses information contained in the continuous prompts. In this
work, we propose Modular Prompt Learning (MPL) that is designed to promote the
preservation of information contained in the inserted prompts. We evaluate the
proposed method on base-to-new generalization and cross-dataset tasks. On
average of 11 datasets, our method achieves 0.7% performance gain on the
base-to-new generalization task compared to the state-of-the-art method. The
largest improvement on the individual dataset is 10.7% (EuroSAT dataset).
