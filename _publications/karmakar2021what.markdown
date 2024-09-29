---
layout: publication
title: What Do Pre45;trained Code Models Know About Code
authors: Karmakar Anjan, Robbes Romain
conference: "Arxiv"
year: 2021
bibkey: karmakar2021what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.11308"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Pre45;trained models of code built on the transformer architecture have performed well on software engineering (SE) tasks such as predictive code generation code summarization among others. However whether the vector representations from these pre45;trained models comprehensively encode characteristics of source code well enough to be applicable to a broad spectrum of downstream tasks remains an open question. One way to investigate this is with diagnostic tasks called probes. In this paper we construct four probing tasks (probing for surface45;level syntactic structural and semantic information) for pre45;trained code models. We show how probes can be used to identify whether models are deficient in (understanding) certain code properties characterize different model layers and get insight into the model sample45;efficiency. We probe four models that vary in their expected knowledge of code properties BERT (pre45;trained on English) CodeBERT and CodeBERTa (pre45;trained on source code and natural language documentation) and GraphCodeBERT (pre45;trained on source code with dataflow). While GraphCodeBERT performs more consistently overall we find that BERT performs surprisingly well on some code tasks which calls for further investigation.
