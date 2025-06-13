---
layout: publication
title: 'Llm2loss: Leveraging Language Models For Explainable Model Diagnostics'
authors: Shervin Ardeshir
conference: "Arxiv"
year: 2023
bibkey: ardeshir2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03212"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Ethics and Bias']
---
Trained on a vast amount of data, Large Language models (LLMs) have achieved
unprecedented success and generalization in modeling fairly complex textual
inputs in the abstract space, making them powerful tools for zero-shot
learning. Such capability is extended to other modalities such as the visual
domain using cross-modal foundation models such as CLIP, and as a result,
semantically meaningful representation are extractable from visual inputs.
  In this work, we leverage this capability and propose an approach that can
provide semantic insights into a model's patterns of failures and biases. Given
a black box model, its training data, and task definition, we first calculate
its task-related loss for each data point. We then extract a semantically
meaningful representation for each training data point (such as CLIP embeddings
from its visual encoder) and train a lightweight diagnosis model which maps
this semantically meaningful representation of a data point to its task loss.
We show that an ensemble of such lightweight models can be used to generate
insights on the performance of the black-box model, in terms of identifying its
patterns of failures and biases.
