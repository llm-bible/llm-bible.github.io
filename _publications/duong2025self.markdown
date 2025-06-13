---
layout: publication
title: 'SCOPE: A Self-supervised Framework For Improving Faithfulness In Conditional Text Generation'
authors: Song Duong, Florian Le Bronnec, Alexandre Allauzen, Vincent Guigue, Alberto Lumbreras, Laure Soulier, Patrick Gallinari
conference: "Arxiv"
year: 2025
bibkey: duong2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13674"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'Applications']
---
Large Language Models (LLMs), when used for conditional text generation,
often produce hallucinations, i.e., information that is unfaithful or not
grounded in the input context. This issue arises in typical conditional text
generation tasks, such as text summarization and data-to-text generation, where
the goal is to produce fluent text based on contextual input. When fine-tuned
on specific domains, LLMs struggle to provide faithful answers to a given
context, often adding information or generating errors. One underlying cause of
this issue is that LLMs rely on statistical patterns learned from their
training data. This reliance can interfere with the model's ability to stay
faithful to a provided context, leading to the generation of ungrounded
information. We build upon this observation and introduce a novel
self-supervised method for generating a training set of unfaithful samples. We
then refine the model using a training process that encourages the generation
of grounded outputs over unfaithful ones, drawing on preference-based training.
Our approach leads to significantly more grounded text generation,
outperforming existing self-supervised techniques in faithfulness, as evaluated
through automatic metrics, LLM-based assessments, and human evaluations.
