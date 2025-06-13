---
layout: publication
title: 'Bayesian Attention Mechanism: A Probabilistic Framework For Positional Encoding And Context Length Extrapolation'
authors: Arthur S. Bianchessi, Rodrigo C. Barros, Lucas S. Kupssinskü
conference: "Arxiv"
year: 2025
bibkey: bianchessi2025bayesian
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22842"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
Transformer-based language models rely on positional encoding (PE) to handle token order and support context length extrapolation. However, existing PE methods lack theoretical clarity and rely on limited evaluation metrics to substantiate their extrapolation claims. We propose the Bayesian Attention Mechanism (BAM), a theoretical framework that formulates positional encoding as a prior within a probabilistic model. BAM unifies existing methods (e.g., NoPE and ALiBi) and motivates a new Generalized Gaussian positional prior that substantially improves long-context generalization. Empirically, BAM enables accurate information retrieval at \\(500\times\\) the training context length, outperforming previous state-of-the-art context length generalization in long context retrieval accuracy while maintaining comparable perplexity and introducing minimal additional parameters.
