---
layout: publication
title: 'Tensorgpt: Efficient Compression Of Large Language Models Based On Tensor-train Decomposition'
authors: Mingxue Xu, Yao Lei Xu, Danilo P. Mandic
conference: "Arxiv"
year: 2023
bibkey: xu2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.00526"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Quantization']
---
High-dimensional token embeddings underpin Large Language Models (LLMs), as
they can capture subtle semantic information and significantly enhance the
modelling of complex language patterns. However, this high dimensionality also
introduces considerable model parameters and prohibitively high model storage
and memory requirements, which is particularly unaffordable for low-end
devices. Targeting no extra training data and insufficient computation cases,
we propose a training-free model compression approach based on the Tensor-Train
Decomposition (TTD), whereby each pre-trained token embedding is converted into
a lower-dimensional Matrix Product State (MPS). We then comprehensively
investigate the low-rank structures extracted by this approach, in terms of the
compression ratio, the language task performance, and latency on a typical
low-end device (i.e. Raspberry Pi). Taking GPT family models (i.e. GPT-2 and
CerebrasGPT) as case studies, our approach theoretically results in \\(46.89%\\)
fewer parameters of the entire model, with a compression ratio \\(39.38\times\\) -
\\(65.64\times\\) for the embedding layers. With different hyperparameter choices,
the model compressed with our approach can achieve a comparable language task
performance to the original model with around \\(2.0\times\\) embedding layer
compression. This empirically proves the existence of low-rank structure in GPT
family models, and demonstrates that about half of the parameters in the
embedding layers are redundant.
