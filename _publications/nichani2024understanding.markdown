---
layout: publication
title: 'Understanding Factual Recall In Transformers Via Associative Memories'
authors: Eshaan Nichani, Jason D. Lee, Alberto Bietti
conference: "Arxiv"
year: 2024
bibkey: nichani2024understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.06538'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models have demonstrated an impressive ability to perform
factual recall. Prior work has found that transformers trained on factual
recall tasks can store information at a rate proportional to their parameter
count. In our work, we show that shallow transformers can use a combination of
associative memories to obtain such near optimal storage capacity. We begin by
proving that the storage capacities of both linear and MLP associative memories
scale linearly with parameter count. We next introduce a synthetic factual
recall task, and prove that a transformer with a single layer of self-attention
followed by an MLP can obtain 100% accuracy on the task whenever either the
total number of self-attention parameters or MLP parameters scales (up to log
factors) linearly with the number of facts. In particular, the transformer can
trade off between using the value matrices or the MLP as an associative memory
to store the dataset of facts. We complement these expressivity results with an
analysis of the gradient flow trajectory of a simplified linear attention model
trained on our factual recall task, where we show that the model exhibits
sequential learning behavior.
