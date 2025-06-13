---
layout: publication
title: 'Realrag: Retrieval-augmented Realistic Image Generation Via Self-reflective Contrastive Learning'
authors: Yuanhuiyi Lyu, Xu Zheng, Lutao Jiang, Yibo Yan, Xin Zou, Huiyu Zhou, Linfeng Zhang, Xuming Hu
conference: "Arxiv"
year: 2025
bibkey: lyu2025retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00848"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Pretraining Methods', 'BERT']
---
Recent text-to-image generative models, e.g., Stable Diffusion V3 and Flux, have achieved notable progress. However, these models are strongly restricted to their limited knowledge, a.k.a., their own fixed parameters, that are trained with closed datasets. This leads to significant hallucinations or distortions when facing fine-grained and unseen novel real-world objects, e.g., the appearance of the Tesla Cybertruck. To this end, we present the first real-object-based retrieval-augmented generation framework (RealRAG), which augments fine-grained and unseen novel object generation by learning and retrieving real-world images to overcome the knowledge gaps of generative models. Specifically, to integrate missing memory for unseen novel object generation, we train a reflective retriever by self-reflective contrastive learning, which injects the generator's knowledge into the sef-reflective negatives, ensuring that the retrieved augmented images compensate for the model's missing knowledge. Furthermore, the real-object-based framework integrates fine-grained visual knowledge for the generative models, tackling the distortion problem and improving the realism for fine-grained object generation. Our Real-RAG is superior in its modular application to all types of state-of-the-art text-to-image generative models and also delivers remarkable performance boosts with all of them, such as a gain of 16.18% FID score with the auto-regressive model on the Stanford Car benchmark.
