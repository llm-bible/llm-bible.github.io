---
layout: publication
title: Transferring Pre45;trained Multimodal Representations With Cross45;modal Similarity Matching
authors: Kim Byoungjip, Choi Sungik, Hwang Dasol, Lee Moontae, Lee Honglak
conference: "Arxiv"
year: 2023
bibkey: kim2023transferring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.02903"}
tags: ['Multimodal Models', 'Prompting', 'Training Techniques']
---
Despite surprising performance on zero45;shot transfer pre45;training a large45;scale multimodal model is often prohibitive as it requires a huge amount of data and computing resources. In this paper we propose a method (BeamCLIP) that can effectively transfer the representations of a large pre45;trained multimodal model (CLIP45;ViT) into a small target model (e.g. ResNet45;18). For unsupervised transfer we introduce cross45;modal similarity matching (CSM) that enables a student model to learn the representations of a teacher model by matching the relative similarity distribution across text prompt embeddings. To better encode the text prompts we design context45;based prompt augmentation (CPA) that can alleviate the lexical ambiguity of input text prompts. Our experiments show that unsupervised representation transfer of a pre45;trained vision45;language model enables a small ResNet45;18 to achieve a better ImageNet45;1K top45;1 linear probe accuracy (66.237;) than vision45;only self45;supervised learning (SSL) methods (e.g. SimCLR 51.837; SwAV 63.737;) while closing the gap with supervised learning (69.837;).
