---
layout: publication
title: 'CLIP With Generative Latent Replay: A Strong Baseline For Incremental Learning'
authors: Emanuele Frascaroli, Aniello Panariello, Pietro Buzzega, Lorenzo Bonicelli, Angelo Porrello, Simone Calderara
conference: "Arxiv"
year: 2024
bibkey: frascaroli2024clip
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.15793'}
  - {name: "Code", url: 'https://github.com/aimagelab/mammoth'}
tags: ['Has Code', 'Transformer', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Multimodal Models', 'Pre-Training', 'Pretraining Methods']
---
With the emergence of Transformers and Vision-Language Models (VLMs) such as
CLIP, fine-tuning large pre-trained models has recently become a prevalent
strategy in Continual Learning. This has led to the development of numerous
prompting strategies to adapt transformer-based models without incurring
catastrophic forgetting. However, these strategies often compromise the
original zero-shot capabilities of the pre-trained CLIP model and struggle to
adapt to domains that significantly deviate from the pre-training data. In this
work, we propose Continual Generative training for Incremental prompt-Learning,
a simple and novel approach to mitigate forgetting while adapting CLIP.
Briefly, we employ Variational Autoencoders (VAEs) to learn class-conditioned
distributions within the embedding space of the visual encoder. We then exploit
these distributions to sample new synthetic visual embeddings and train the
corresponding class-specific textual prompts during subsequent tasks. Through
extensive experiments on different domains, we show that such a generative
replay approach can adapt to new tasks while improving zero-shot capabilities,
evaluated using a novel metric tailored for CL scenarios. Notably, further
analysis reveals that our approach can bridge the gap with joint prompt tuning.
The codebase is available at https://github.com/aimagelab/mammoth.
