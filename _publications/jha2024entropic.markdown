---
layout: publication
title: 'Relu''s Revival: On The Entropic Overload In Normalization-free Large Language Models'
authors: Nandan Kumar Jha, Brandon Reagen
conference: "Arxiv"
year: 2024
bibkey: jha2024entropic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.09637'}
  - {name: "Code", url: 'https://github.com/Nandan91/relu-revival-normfree'}
tags: ['Attention Mechanism', 'Has Code', 'Interpretability and Explainability', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
LayerNorm is a critical component in modern large language models (LLMs) for
stabilizing training and ensuring smooth optimization. However, it introduces
significant challenges in mechanistic interpretability, outlier feature
suppression, faithful signal propagation, and computational and communication
complexity of private inference. This work explores desirable activation
functions in normalization-free decoder-only LLMs. Contrary to the conventional
preference for the GELU in transformer-based models, our empirical findings
demonstrate an \{\em opposite trend\} -- ReLU significantly outperforms GELU in
LayerNorm-free models, leading to an \{\bf 8.2%\} perplexity improvement. We
discover a key issue with GELU, where early layers experience entropic
overload, leading to the under-utilization of the representational capacity of
attention heads. This highlights that smoother activations like GELU are \{\em
ill-suited\} for LayerNorm-free architectures, whereas ReLU's geometrical
properties -- specialization in input space and intra-class selectivity -- lead
to improved learning dynamics and better information retention in the absence
of LayerNorm. This study offers key insights for optimizing transformer
architectures where LayerNorm introduces significant challenges. The code and
implementation are available at
https://github.com/Nandan91/relu-revival-normfree
