---
layout: publication
title: ECLIPSE A Resource45;efficient Text45;to45;image Prior For Image Generations
authors: Patel Maitreya, Kim Changhoon, Cheng Sheng, Baral Chitta, Yang Yezhou
conference: "Arxiv"
year: 2023
bibkey: patel2023resource
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04655"}
tags: ['Merging', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Text45;to45;image (T2I) diffusion models notably the unCLIP models (e.g. DALL45;E45;2) achieve state45;of45;the45;art (SOTA) performance on various compositional T2I benchmarks at the cost of significant computational resources. The unCLIP stack comprises T2I prior and diffusion image decoder. The T2I prior model alone adds a billion parameters compared to the Latent Diffusion Models which increases the computational and high45;quality data requirements. We introduce ECLIPSE a novel contrastive learning method that is both parameter and data45;efficient. ECLIPSE leverages pre45;trained vision45;language models (e.g. CLIP) to distill the knowledge into the prior model. We demonstrate that the ECLIPSE trained prior with only 3.337; of the parameters and trained on a mere 2.837; of the data surpasses the baseline T2I priors with an average of 71.637; preference score under resource45;limited setting. It also attains performance on par with SOTA big models achieving an average of 63.3637; preference score in terms of the ability to follow the text compositions. Extensive experiments on two unCLIP diffusion image decoders Karlo and Kandinsky affirm that ECLIPSE priors consistently deliver high performance while significantly reducing resource dependency.
