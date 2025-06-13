---
layout: publication
title: 'Fast Multi-step Critiquing For Vae-based Recommender Systems'
authors: Diego Antognini, Boi Faltings
conference: "Arxiv"
year: 2021
bibkey: antognini2021fast
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2105.00774'}
tags: ['Interpretability and Explainability', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'RecSys', 'Multimodal Models', 'Reinforcement Learning']
---
Recent studies have shown that providing personalized explanations alongside
recommendations increases trust and perceived quality. Furthermore, it gives
users an opportunity to refine the recommendations by critiquing parts of the
explanations. On one hand, current recommender systems model the
recommendation, explanation, and critiquing objectives jointly, but this
creates an inherent trade-off between their respective performance. On the
other hand, although recent latent linear critiquing approaches are built upon
an existing recommender system, they suffer from computational inefficiency at
inference due to the objective optimized at each conversation's turn. We
address these deficiencies with M&Ms-VAE, a novel variational autoencoder for
recommendation and explanation that is based on multimodal modeling
assumptions. We train the model under a weak supervision scheme to simulate
both fully and partially observed variables. Then, we leverage the
generalization ability of a trained M&Ms-VAE model to embed the user preference
and the critique separately. Our work's most important innovation is our
critiquing module, which is built upon and trained in a self-supervised manner
with a simple ranking objective. Experiments on four real-world datasets
demonstrate that among state-of-the-art models, our system is the first to
dominate or match the performance in terms of recommendation, explanation, and
multi-step critiquing. Moreover, M&Ms-VAE processes the critiques up to 25.6x
faster than the best baselines. Finally, we show that our model infers coherent
joint and cross generation, even under weak supervision, thanks to our
multimodal-based modeling and training scheme.
