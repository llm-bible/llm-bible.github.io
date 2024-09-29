---
layout: publication
title: LlaMaVAE Guiding Large Language Model Generation via Continuous Latent Sentence Spaces
authors: Zhang Yingji, Carvalho Danilo S., Pratt-hartmann Ian, Freitas André
conference: "Arxiv"
year: 2023
bibkey: zhang2023llamavae
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.13208"}
tags: ['Applications', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning']
---
Deep generative neural networks such as Variational AutoEncoders (VAEs) offer an opportunity to better understand and control language models from the perspective of sentence-level latent spaces. To combine the controllability of VAE latent spaces with the state-of-the-art performance of recent large language models (LLMs) we present in this work LlaMaVAE which combines expressive encoder and decoder models (sentenceT5 and LlaMA) with a VAE architecture aiming to provide better text generation control to LLMs. In addition to conditionally guide the VAE generation we investigate a new approach based on flow-based invertible neural networks (INNs) named Invertible CVAE. Experimental results reveal that LlaMaVAE can outperform the previous state-of-the-art VAE language model Optimus across various tasks including language modelling semantic textual similarity and definition modelling. Qualitative analysis on interpolation and traversal experiments also indicates an increased degree of semantic clustering and geometric consistency which enables better generation control.
