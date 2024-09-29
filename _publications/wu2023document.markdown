---
layout: publication
title: "Document Flattening: Beyond Concatenating Context For Document-level Neural Machine Translation"
authors: Wu Minghao, Foster George, Qu Lizhen, Haffari Gholamreza
conference: "Arxiv"
year: 2023
bibkey: wu2023document
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.08079"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Existing work in document-level neural machine translation commonly concatenates several consecutive sentences as a pseudo-document and then learns inter-sentential dependencies. This strategy limits the models ability to leverage information from distant context. We overcome this limitation with a novel Document Flattening (DocFlat) technique that integrates Flat-Batch Attention (FBA) and Neural Context Gate (NCG) into Transformer model to utilize information beyond the pseudo-document boundaries. FBA allows the model to attend to all the positions in the batch and learns the relationships between positions explicitly and NCG identifies the useful information from the distant context. We conduct comprehensive experiments and analyses on three benchmark datasets for English-German translation and validate the effectiveness of two variants of DocFlat. Empirical results show that our approach outperforms strong baselines with statistical significance on BLEU COMET and accuracy on the contrastive test set. The analyses highlight that DocFlat is highly effective in capturing the long-range information.
