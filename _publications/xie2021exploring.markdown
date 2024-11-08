---
layout: publication
title: 'Exploring Story Generation With Multi-task Objectives In Variational Autoencoders'
authors: Xie Zhuohan, Cohn Trevor, Lau Jey Han
conference: "Arxiv"
year: 2021
bibkey: xie2021exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.08133"}
tags: ['BERT', 'GPT', 'Model Architecture', 'RAG']
---
GPT-2 has been frequently adapted in story generation models as it provides
powerful generative capability. However, it still fails to generate consistent
stories and lacks diversity. Current story generation models leverage
additional information such as plots or commonsense into GPT-2 to guide the
generation process. These approaches focus on improving generation quality of
stories while our work look at both quality and diversity. We explore combining
BERT and GPT-2 to build a variational autoencoder (VAE), and extend it by
adding additional objectives to learn global features such as story topic and
discourse relations. Our evaluations show our enhanced VAE can provide better
quality and diversity trade off, generate less repetitive story content and
learn a more informative latent variable.
