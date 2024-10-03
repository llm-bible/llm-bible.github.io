---
layout: publication
title: 'Adversarial Self-attention For Language Understanding'
authors: Wu Hongqiu, Ding Ruixue, Zhao Hai, Xie Pengjun, Huang Fei, Zhang Min
conference: "Arxiv"
year: 2022
bibkey: wu2022adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.12608"}
tags: ['Attention Mechanism', 'BERT', 'Ethics And Bias', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security', 'Training Techniques', 'Transformer']
---
Deep neural models (e.g. Transformer) naturally learn spurious features, which create a shortcut'' between the labels and inputs, thus impairing the generalization and robustness. This paper advances the self-attention mechanism to its robust variant for Transformer-based pre-trained language models (e.g. BERT). We propose \textit\{Adversarial Self-Attention\} mechanism (ASA), which adversarially biases the attentions to effectively suppress the model reliance on features (e.g. specific keywords) and encourage its exploration of broader semantics. We conduct a comprehensive evaluation across a wide range of tasks for both pre-training and fine-tuning stages. For pre-training, ASA unfolds remarkable performance gains compared to naive training for longer steps. For fine-tuning, ASA-empowered models outweigh naive models by a large margin considering both generalization and robustness.
