---
layout: publication
title: Language Detoxification With Attribute-discriminative Latent Space
authors: Kwak Jin Myung, Kim Minseon, Hwang Sung Ju
conference: "Arxiv"
year: 2022
bibkey: kwak2022language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.10329"}
tags: ['Applications', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Transformer-based Language Models (LMs) have achieved impressive results on natural language understanding tasks but they can also generate toxic text such as insults threats and profanity limiting their real-world applications. To overcome this issue a few text generation approaches aim to detoxify toxic texts using additional LMs or perturbations. However previous methods require excessive memory computations and time which are serious bottlenecks in their real-world application. To address such limitations we propose an effective yet efficient method for language detoxification using an attribute-discriminative latent space. Specifically we project the latent space of an original Transformer LM onto a discriminative latent space that well-separates texts by their attributes using a projection block and an attribute discriminator. This allows the LM to control the text generation to be non-toxic with minimal memory and computation overhead. We validate our model Attribute-Discriminative Language Model (ADLM) on detoxified language and dialogue generation tasks on which our method significantly outperforms baselines both in performance and efficiency.
