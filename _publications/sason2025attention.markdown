---
layout: publication
title: 'Attention Condensation Via Sparsity Induced Regularized Training'
authors: Eli Sason, Darya Frolova, Boris Nazarov, Felix Goldberd
conference: "Arxiv"
year: 2025
bibkey: sason2025attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01564"}
tags: ['Transformer', 'Tools', 'GPT', 'Pruning', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
As the context window expands, self-attention increasingly dominates the
transformer's inference time. Therefore, accelerating attention computation
while minimizing performance degradation is essential for the efficient
deployment of Large Language Models (LLMs). In this study we extend a
theoretical framework of attention sparsity in LLMs. A customized loss function
is designed to enforce the sparsity by restricting the number of top elements
in the attention matrix. We perform an initial set of evaluations with GPT-2 to
show the effectiveness of our sparsification approach. The attention matrices
of the models trained with the proposed loss are both sparse and effective in
capturing relevant input dependencies. We now continue working to demonstrate
the value of our approach on larger models and different architectures.
