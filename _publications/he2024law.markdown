---
layout: publication
title: 'A Law Of Next-token Prediction In Large Language Models'
authors: Hangfeng He, Weijie J. Su
conference: "Arxiv"
year: 2024
bibkey: he2024law
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13442"}
tags: ['Transformer', 'Pre-Training', 'Applications', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have been widely employed across various
application domains, yet their black-box nature poses significant challenges to
understanding how these models process input data internally to make
predictions. In this paper, we introduce a precise and quantitative law that
governs the learning of contextualized token embeddings through intermediate
layers in pre-trained LLMs for next-token prediction. Our findings reveal that
each layer contributes equally to enhancing prediction accuracy, from the
lowest to the highest layer -- a universal phenomenon observed across a diverse
array of open-source LLMs, built on architectures such as Transformer, RWKV,
and Mamba. We demonstrate that this law offers new perspectives and insights to
inform and guide practices in LLM development and applications, including model
scaling, pre-training tasks, and information flow. Overall, our law enables
more fine-grained approaches to the design, training, and interpretation of
LLMs through scrutinizing their internal data processing mechanisms.
