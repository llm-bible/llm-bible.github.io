---
layout: publication
title: 'Latim: Measuring Latent Token-to-token Interactions In Mamba Models'
authors: Hugo Pitorro, Marcos Treviso
conference: "Arxiv"
year: 2025
bibkey: pitorro2025measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15612"}
tags: ['Model Architecture', 'Tools', 'Pretraining Methods', 'Transformer', 'Interpretability and Explainability', 'Applications', 'Attention Mechanism']
---
State space models (SSMs), such as Mamba, have emerged as an efficient
alternative to transformers for long-context sequence modeling. However,
despite their growing adoption, SSMs lack the interpretability tools that have
been crucial for understanding and improving attention-based architectures.
While recent efforts provide insights into Mamba's internal mechanisms, they do
not explicitly decompose token-wise contributions, leaving gaps in
understanding how Mamba selectively processes sequences across layers. In this
work, we introduce LaTIM, a novel token-level decomposition method for both
Mamba-1 and Mamba-2 that enables fine-grained interpretability. We extensively
evaluate our method across diverse tasks, including machine translation,
copying, and retrieval-based generation, demonstrating its effectiveness in
revealing Mamba's token-to-token interaction patterns.
