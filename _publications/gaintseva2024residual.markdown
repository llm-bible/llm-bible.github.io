---
layout: publication
title: RAVE Residual Vector Embedding For Clip45;guided Backlit Image Enhancement
authors: Gaintseva Tatiana, Benning Martin, Slabaugh Gregory
conference: "Arxiv"
year: 2024
bibkey: gaintseva2024residual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01889"}
tags: ['Bias Mitigation', 'Ethics And Bias', 'Prompting', 'Tools', 'Training Techniques']
---
In this paper we propose a novel modification of Contrastive Language45;Image Pre45;Training (CLIP) guidance for the task of unsupervised backlit image enhancement. Our work builds on the state45;of45;the45;art CLIP45;LIT approach which learns a prompt pair by constraining the text45;image similarity between a prompt (negative/positive sample) and a corresponding image (backlit image/well45;lit image) in the CLIP embedding space. Learned prompts then guide an image enhancement network. Based on the CLIP45;LIT framework we propose two novel methods for CLIP guidance. First we show that instead of tuning prompts in the space of text embeddings it is possible to directly tune their embeddings in the latent space without any loss in quality. This accelerates training and potentially enables the use of additional encoders that do not have a text encoder. Second we propose a novel approach that does not require any prompt tuning. Instead based on CLIP embeddings of backlit and well45;lit images from training data we compute the residual vector in the embedding space as a simple difference between the mean embeddings of the well45;lit and backlit images. This vector then guides the enhancement network during training pushing a backlit image towards the space of well45;lit images. This approach further dramatically reduces training time stabilizes training and produces high quality enhanced images without artifacts both in supervised and unsupervised training regimes. Additionally we show that residual vectors can be interpreted revealing biases in training data and thereby enabling potential bias correction.
