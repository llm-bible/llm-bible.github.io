---
layout: publication
title: 'Partially Rewriting A Transformer In Natural Language'
authors: Gonçalo Paulo, Nora Belrose
conference: "Arxiv"
year: 2025
bibkey: paulo2025partially
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.18838"}
tags: ['Pretraining Methods', 'Model Architecture', 'Transformer', 'Interpretability and Explainability']
---
The greatest ambition of mechanistic interpretability is to completely
rewrite deep neural networks in a format that is more amenable to human
understanding, while preserving their behavior and performance. In this paper,
we attempt to partially rewrite a large language model using simple natural
language explanations. We first approximate one of the feedforward networks in
the LLM with a wider MLP with sparsely activating neurons - a transcoder - and
use an automated interpretability pipeline to generate explanations for these
neurons. We then replace the first layer of this sparse MLP with an LLM-based
simulator, which predicts the activation of each neuron given its explanation
and the surrounding context. Finally, we measure the degree to which these
modifications distort the model's final output. With our pipeline, the model's
increase in loss is statistically similar to entirely replacing the sparse MLP
output with the zero vector. We employ the same protocol, this time using a
sparse autoencoder, on the residual stream of the same layer and obtain similar
results. These results suggest that more detailed explanations are needed to
improve performance substantially above the zero ablation baseline.
