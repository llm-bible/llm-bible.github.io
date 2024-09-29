---
layout: publication
title: Pre45;trained Language Models Do Not Help Auto45;regressive Text45;to45;image Generation
authors: Zhang Yuhui, Mckinzie Brandon, Gan Zhe, Shankar Vaishaal, Toshev Alexander
conference: "Arxiv"
year: 2023
bibkey: zhang2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16201"}
tags: ['Applications', 'Interpretability And Explainability', 'Language Modeling', 'RAG', 'Training Techniques']
---
Recent advances in image tokenizers such as VQ45;VAE have enabled text45;to45;image generation using auto45;regressive methods similar to language modeling. However these methods have yet to leverage pre45;trained language models despite their adaptability to various downstream tasks. In this work we explore this gap by adapting a pre45;trained language model for auto45;regressive text45;to45;image generation and find that pre45;trained language models offer limited help. We provide a two45;fold explanation by analyzing tokens from each modality. First we demonstrate that image tokens possess significantly different semantics compared to text tokens rendering pre45;trained language models no more effective in modeling them than randomly initialized ones. Second the text tokens in the image45;text datasets are too simple compared to normal language model pre45;training data which causes the catastrophic degradation of language models capability.
