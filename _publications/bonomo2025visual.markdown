---
layout: publication
title: 'Visual RAG: Expanding MLLM Visual Knowledge Without Fine-tuning'
authors: Mirco Bonomo, Simone Bianco
conference: "Arxiv"
year: 2025
bibkey: bonomo2025visual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.10834'}
tags: ['ACL', 'In-Context Learning', 'Few-Shot', 'RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Multimodal Models', 'TACL', 'Pretraining Methods']
---
Multimodal Large Language Models (MLLMs) have achieved notable performance in
computer vision tasks that require reasoning across visual and textual
modalities, yet their capabilities are limited to their pre-trained data,
requiring extensive fine-tuning for updates. Recent researches have explored
the use of In-Context Learning (ICL) to overcome these challenges by providing
a set of demonstrating examples as context to augment MLLMs performance in
several tasks, showing that many-shot ICL leads to substantial improvements
compared to few-shot ICL. However, the reliance on numerous demonstrating
examples and the limited MLLMs context windows presents significant obstacles.
This paper aims to address these challenges by introducing a novel approach,
Visual RAG, that synergically combines the MLLMs capability to learn from the
context, with a retrieval mechanism. The crux of this approach is to ensure to
augment the MLLM knowledge by selecting only the most relevant demonstrating
examples for the query, pushing it to learn by analogy. In this way, relying on
the new information provided dynamically during inference time, the resulting
system is not limited to the knowledge extracted from the training data, but
can be updated rapidly and easily without fine-tuning. Furthermore, this
greatly reduces the computational costs for improving the model image
classification performance, and augments the model knowledge to new visual
domains and tasks it was not trained for. Extensive experiments on eight
different datasets in the state of the art spanning several domains and image
classification tasks show that the proposed Visual RAG, compared to the most
recent state of the art (i.e., many-shot ICL), is able to obtain an accuracy
that is very close or even higher (approx. +2% improvement on average) while
using a much smaller set of demonstrating examples (approx. only 23% on
average).
