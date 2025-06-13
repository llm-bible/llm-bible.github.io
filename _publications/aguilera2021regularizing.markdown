---
layout: publication
title: 'Regularizing Transformers With Deep Probabilistic Layers'
authors: Aurora Cobo Aguilera, Pablo Martínez Olmos, Antonio Artés-rodríguez, Fernando Pérez-cruz
conference: "Arxiv"
year: 2021
bibkey: aguilera2021regularizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.10764"}
tags: ['Model Architecture', 'Pretraining Methods', 'BERT', 'Transformer', 'Attention Mechanism']
---
Language models (LM) have grown with non-stop in the last decade, from
sequence-to-sequence architectures to the state-of-the-art and utter
attention-based Transformers. In this work, we demonstrate how the inclusion of
deep generative models within BERT can bring more versatile models, able to
impute missing/noisy words with richer text or even improve BLEU score. More
precisely, we use a Gaussian Mixture Variational Autoencoder (GMVAE) as a
regularizer layer and prove its effectiveness not only in Transformers but also
in the most relevant encoder-decoder based LM, seq2seq with and without
attention.
