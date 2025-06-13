---
layout: publication
title: 'Inheritune: Training Smaller Yet More Attentive Language Models'
authors: Sunny Sanyal, Ravid Shwartz-ziv, Alexandros G. Dimakis, Sujay Sanghavi
conference: "Arxiv"
year: 2024
bibkey: sanyal2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08634"}
  - {name: "Code", url: "https://github.com/sanyalsunny111/LLM-Inheritune"}
tags: ['Transformer', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Large Language Models (LLMs) have achieved remarkable performance across
various natural language processing tasks, primarily due to the transformer
architecture and its self-attention mechanism. However, we observe that in
standard decoder-style LLMs, attention matrices degenerate to single-column for
deeper layers. Layers in this state are unable to learn anything meaningful and
mostly redundant; we refer to these as lazy layers. The goal of this paper is
to train smaller models by eliminating this structural inefficiency without
compromising performance.
  Motivated by this observation, we propose Inheritune, a simple yet effective
training recipe for developing smaller, high-performing language models.
Smaller models trained with Inheritune, inherit early transformer layers from a
larger pre-trained model, then retrain and progressively expand until they
match or exceed the performance of the larger model. We demonstrate that
Inheritune enables the training of various sizes of GPT-2 models on datasets
like OpenWebText-9B and FineWeb_edu. Models trained with Inheritune, despite
having significantly fewer layers, match or even surpass the performance of
their larger counterparts. For instance, our 16-layer GPT-2 medium variant
achieves comparable performance to the standard 24-layer GPT-2 medium model.
Code is available at https://github.com/sanyalsunny111/LLM-Inheritune.
