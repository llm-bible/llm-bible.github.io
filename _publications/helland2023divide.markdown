---
layout: publication
title: 'Divide Et Impera: Multi-transformer Architectures For Complex Nlp-tasks'
authors: Solveig Helland, Elena Gavagnin, Alexandre De Spindler
conference: "Proceedings of the 8th edition of the Swiss Text Analytics Conference 2023 Neuchatel Switzerland. Association for Computational Linguistics"
year: 2023
bibkey: helland2023divide
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.16897'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
The growing capabilities of transformer models pave the way for solving
increasingly complex NLP tasks. A key to supporting application-specific
requirements is the ability to fine-tune. However, compiling a fine-tuning
dataset tailored to complex tasks is tedious and results in large datasets,
limiting the ability to control transformer output. We present an approach in
which complex tasks are divided into simpler subtasks. Multiple transformer
models are fine-tuned to one subtask each, and lined up to accomplish the
complex task. This simplifies the compilation of fine-tuning datasets and
increases overall controllability. Using the example of reducing gender bias as
a complex task, we demonstrate our approach and show that it performs better
than using a single model.
