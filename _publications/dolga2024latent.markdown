---
layout: publication
title: Latent Attention for Linear Time Transformers
authors: Dolga Rares, Cobzarenco Marius, Barber David
conference: "Arxiv"
year: 2024
bibkey: dolga2024latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17512"}
tags: ['ARXIV', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
The time complexity of the standard attention mechanism in a transformer scales quadratically with the length of the sequence. We introduce a method to reduce this to linear scaling with time based on defining attention via latent vectors. The method is readily usable as a drop-in replacement for the standard attention mechanism. Our Latte Transformer model can be implemented for both bidirectional and unidirectional tasks with the causal version allowing a recurrent implementation which is memory and time-efficient during inference of language generation tasks. Whilst next token prediction scales linearly with the sequence length for a standard transformer a Latte Transformer requires constant time to compute the next token. The empirical performance of our method is comparable to standard attention yet allows scaling to context windows much larger than practical in standard attention.
