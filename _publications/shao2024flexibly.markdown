---
layout: publication
title: 'Flexibly Scaling Large Language Models Contexts Through Extensible Tokenization'
authors: Ninglu Shao, Shitao Xiao, Zheng Liu, Peitian Zhang
conference: "Arxiv"
year: 2024
bibkey: shao2024flexibly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07793"}
tags: ['Fine-Tuning', 'Applications', 'Training Techniques', 'Tokenization', 'Pretraining Methods', 'Few-Shot']
---
Large language models (LLMs) are in need of sufficient contexts to handle
many critical applications, such as retrieval augmented generation and few-shot
learning. However, due to the constrained window size, the LLMs can only access
to the information within a limited context. Although the size of context
window can be extended by fine-tuning, it will result in a substantial cost in
both training and inference stage. In this paper, we present Extensible
Tokenization as an alternative method which realizes the flexible scaling of
LLMs' context. Extensible Tokenization stands as a midware in between of the
tokenized context and the LLM, which transforms the raw token embeddings into
the extensible embeddings. Such embeddings provide a more compact
representation for the long context, on top of which the LLM is able to
perceive more information with the same context window. Extensible Tokenization
is also featured by its flexibility: the scaling factor can be flexibly
determined within a feasible scope, leading to the extension of an arbitrary
context length at the inference time. Besides, Extensible Tokenization is
introduced as a drop-in component, which can be seamlessly plugged into not
only the LLM itself and but also its fine-tuned derivatives, bringing in the
extended contextual information while fully preserving the LLM's existing
capabilities. We perform comprehensive experiments on long-context language
modeling and understanding tasks, which verify Extensible Tokenization as an
effective, efficient, flexible, and compatible method to extend LLM's context.
Our model and source code will be made publicly available.
