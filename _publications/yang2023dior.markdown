---
layout: publication
title: Dior45;cvae Pre45;trained Language Models And Diffusion Priors For Variational Dialog Generation
authors: Yang Tianyu, Tran Thy Thy, Gurevych Iryna
conference: "Arxiv"
year: 2023
bibkey: yang2023dior
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15025"}
  - {name: "Code", url: "https://github.com/UKPLab/dior&#45;cvae"}
tags: ['Attention Mechanism', 'Has Code', 'Merging', 'Model Architecture', 'RAG', 'Training Techniques', 'Transformer']
---
Current variational dialog models have employed pre45;trained language models (PLMs) to parameterize the likelihood and posterior distributions. However the Gaussian assumption made on the prior distribution is incompatible with these distributions thus restricting the diversity of generated responses. These models also suffer from posterior collapse i.e. the decoder tends to ignore latent variables and directly access information captured in the encoder through the cross45;attention mechanism. In this work we propose Dior45;CVAE a hierarchical conditional variational autoencoder (CVAE) with diffusion priors to address these challenges. We employ a diffusion model to increase the complexity of the prior distribution and its compatibility with the distributions produced by a PLM. Also we propose memory dropout to the cross45;attention mechanism which actively encourages the use of latent variables for response generation. Overall experiments across two commonly used open45;domain dialog datasets show that our method can generate more diverse responses without large45;scale dialog pre45;training. Code is available at https://github.com/UKPLab/dior&#45;cvae.
