---
layout: publication
title: Codet5 Identifier45;aware Unified Pre45;trained Encoder45;decoder Models For Code Understanding And Generation
authors: Wang Yue, Wang Weishi, Joty Shafiq, Hoi Steven C. H.
conference: "Arxiv"
year: 2021
bibkey: wang2021identifier
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.00859"}
tags: ['BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Pre45;trained models for Natural Languages (NL) like BERT and GPT have been recently shown to transfer well to Programming Languages (PL) and largely benefit a broad set of code45;related tasks. Despite their success most current methods either rely on an encoder45;only (or decoder45;only) pre45;training that is suboptimal for generation (resp. understanding) tasks or process the code snippet in the same way as NL neglecting the special characteristics of PL such as token types. We present CodeT5 a unified pre45;trained encoder45;decoder Transformer model that better leverages the code semantics conveyed from the developer45;assigned identifiers. Our model employs a unified framework to seamlessly support both code understanding and generation tasks and allows for multi45;task learning. Besides we propose a novel identifier45;aware pre45;training task that enables the model to distinguish which code tokens are identifiers and to recover them when they are masked. Furthermore we propose to exploit the user45;written code comments with a bimodal dual generation task for better NL45;PL alignment. Comprehensive experiments show that CodeT5 significantly outperforms prior methods on understanding tasks such as code defect detection and clone detection and generation tasks across various directions including PL45;NL NL45;PL and PL45;PL. Further analysis reveals that our model can better capture semantic information from code. Our code and pre45;trained models are released at https github.com/salesforce/CodeT5 .
