---
layout: publication
title: 'Steered Generation Via Gradient Descent On Sparse Features'
authors: Sumanta Bhattacharyya, Pedram Rooshenas
conference: "Arxiv"
year: 2025
bibkey: bhattacharyya2025steered
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18644"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Attention Mechanism', 'Model Architecture']
---
Large language models (LLMs) encode a diverse range of linguistic features
within their latent representations, which can be harnessed to steer their
output toward specific target characteristics. In this paper, we modify the
internal structure of LLMs by training sparse autoencoders to learn a sparse
representation of the query embedding, allowing precise control over the
model's attention distribution. We demonstrate that manipulating this sparse
representation effectively transforms the output toward different stylistic and
cognitive targets. Specifically, in an educational setting, we show that the
cognitive complexity of LLM-generated feedback can be systematically adjusted
by modifying the encoded query representation at a specific layer. To achieve
this, we guide the learned sparse embedding toward the representation of
samples from the desired cognitive complexity level, using gradient-based
optimization in the latent space.
