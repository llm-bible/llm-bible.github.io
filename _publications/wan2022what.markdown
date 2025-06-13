---
layout: publication
title: 'What Do They Capture? -- A Structural Analysis Of Pre-trained Language Models For Source Code'
authors: Yao Wan, Wei Zhao, Hongyu Zhang, Yulei Sui, Guandong Xu, Hai Jin
conference: "Arxiv"
year: 2022
bibkey: wan2022what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.06840"}
tags: ['Transformer', 'Pre-Training', 'Applications', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'BERT']
---
Recently, many pre-trained language models for source code have been proposed
to model the context of code and serve as a basis for downstream code
intelligence tasks such as code completion, code search, and code
summarization. These models leverage masked pre-training and Transformer and
have achieved promising results. However, currently there is still little
progress regarding interpretability of existing pre-trained code models. It is
not clear why these models work and what feature correlations they can capture.
In this paper, we conduct a thorough structural analysis aiming to provide an
interpretation of pre-trained language models for source code (e.g., CodeBERT,
and GraphCodeBERT) from three distinctive perspectives: (1) attention analysis,
(2) probing on the word embedding, and (3) syntax tree induction. Through
comprehensive analysis, this paper reveals several insightful findings that may
inspire future studies: (1) Attention aligns strongly with the syntax structure
of code. (2) Pre-training language models of code can preserve the syntax
structure of code in the intermediate representations of each Transformer
layer. (3) The pre-trained models of code have the ability of inducing syntax
trees of code. Theses findings suggest that it may be helpful to incorporate
the syntax structure of code into the process of pre-training for better code
representations.
