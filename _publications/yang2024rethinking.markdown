---
layout: publication
title: Rethinking Tokenization Crafting Better Tokenizers for Large Language Models
authors: Yang Jinbiao
conference: "Arxiv"
year: 2024
bibkey: yang2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.00417"}
tags: ['Pretraining Methods', 'TOKENIZATION', 'Tools', 'Training Techniques']
---
Tokenization significantly influences language models(LMs) performance. This paper traces the evolution of tokenizers from word-level to subword-level analyzing how they balance tokens and types to enhance model adaptability while controlling complexity. Despite subword tokenizers like Byte Pair Encoding (BPE) overcoming many word tokenizer limitations they encounter difficulties in handling non-Latin languages and depend heavily on extensive training data and computational resources to grasp the nuances of multiword expressions (MWEs). This article argues that tokenizers more than mere technical tools should drawing inspiration from the cognitive science about human language processing. This study then introduces the Principle of Least Effort from cognitive science that humans naturally seek to reduce cognitive effort and discusses the benefits of this principle for tokenizer development. Based on this principle the paper proposes that the Less-is-Better (LiB) model could be a new approach for LLM tokenizer. The LiB model can autonomously learn an integrated vocabulary consisting of subwords words and MWEs which effectively reduces both the numbers of tokens and types. Comparative evaluations show that the LiB tokenizer outperforms existing word and BPE tokenizers presenting an innovative method for tokenizer development and hinting at the possibility of future cognitive science-based tokenizers being more efficient.
