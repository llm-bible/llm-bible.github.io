---
layout: publication
title: Retrieval-Pretrained Transformer Long-range Language Modeling with Self-retrieval
authors: Rubin Ohad, Berant Jonathan
conference: "Arxiv"
year: 2023
bibkey: rubin2023retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.13421"}
tags: ['ARXIV', 'Language Modeling', 'Model Architecture', 'Transformer']
---
Retrieval-augmented language models (LMs) have received much attention recently. However typically the retriever is not trained jointly as a native component of the LM but added post-hoc to an already-pretrained LM which limits the ability of the LM and the retriever to adapt to one another. In this work we propose the Retrieval-Pretrained Transformer (RPT) an architecture and training procedure for jointly training a retrieval-augmented LM from scratch and apply it to the task of modeling long texts. Given a recently generated text chunk in a long document the LM computes query representations which are then used to retrieve earlier chunks in the document located potentially tens of thousands of tokens before. Information from retrieved chunks is fused into the LM representations to predict the next target chunk. We train the retriever component with a semantic objective where the goal is to retrieve chunks that increase the probability of the next chunk according to a reference LM. We evaluate RPT on four long-range language modeling tasks spanning books code and mathematical writing and demonstrate that RPT improves retrieval quality and subsequently perplexity across the board compared to strong baselines.
