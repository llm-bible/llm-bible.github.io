---
layout: publication
title: 'ECLIPSE: A Resource-efficient Text-to-image Prior For Image Generations'
authors: Patel Maitreya, Kim Changhoon, Cheng Sheng, Baral Chitta, Yang Yezhou
conference: "Arxiv"
year: 2023
bibkey: patel2023resource
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04655"}
tags: ['Merging', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
"Text-to-image (T2I) diffusion models, notably the unCLIP models (e.g., DALL-E-2), achieve state-of-the-art (SOTA) performance on various compositional T2I benchmarks, at the cost of significant computational resources. The unCLIP stack comprises T2I prior and diffusion image decoder. The T2I prior model alone adds a billion parameters compared to the Latent Diffusion Models, which increases the computational and high-quality data requirements. We introduce ECLIPSE, a novel contrastive learning method that is both parameter and data-efficient. ECLIPSE leverages pre-trained vision-language models (e.g., CLIP) to distill the knowledge into the prior model. We demonstrate that the ECLIPSE trained prior, with only 3.3&#37; of the parameters and trained on a mere 2.8&#37; of the data, surpasses the baseline T2I priors with an average of 71.6&#37; preference score under resource-limited setting. It also attains performance on par with SOTA big models, achieving an average of 63.36&#37; preference score in terms of the ability to follow the text compositions. Extensive experiments on two unCLIP diffusion image decoders, Karlo and Kandinsky, affirm that ECLIPSE priors consistently deliver high performance while significantly reducing resource dependency."
