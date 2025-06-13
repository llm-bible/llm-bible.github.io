---
layout: publication
title: 'Context-aware Prompt Tuning: Advancing In-context Learning With Adversarial Methods'
authors: Tsachi Blau, Moshe Kimhi, Yonatan Belinkov, Alexander Bronstein, Chaim Baskin
conference: "Arxiv"
year: 2024
bibkey: blau2024context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.17222"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Fine-tuning Large Language Models (LLMs) typically involves updating at least
a few billions of parameters. A more parameter-efficient approach is Prompt
Tuning (PT), which updates only a few learnable tokens, and differently,
In-Context Learning (ICL) adapts the model to a new task by simply including
examples in the input without any training. When applying optimization-based
methods, such as fine-tuning and PT for few-shot learning, the model is
specifically adapted to the small set of training examples, whereas ICL leaves
the model unchanged. This distinction makes traditional learning methods more
prone to overfitting; in contrast, ICL is less sensitive to the few-shot
scenario. While ICL is not prone to overfitting, it does not fully extract the
information that exists in the training examples. This work introduces
Context-aware Prompt Tuning (CPT), a method inspired by ICL, PT, and
adversarial attacks. We build on the ICL strategy of concatenating examples
before the input, but we extend this by PT-like learning, refining the context
embedding through iterative optimization to extract deeper insights from the
training examples. We carefully modify specific context tokens, considering the
unique structure of input and output formats. Inspired by adversarial attacks,
we adjust the input based on the labels present in the context, focusing on
minimizing, rather than maximizing, the loss. Moreover, we apply a projected
gradient descent algorithm to keep token embeddings close to their original
values, under the assumption that the user-provided data is inherently
valuable. Our method has been shown to achieve superior accuracy across
multiple classification tasks using various LLM models.
