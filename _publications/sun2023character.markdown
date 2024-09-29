---
layout: publication
title: Character45;level Chinese Backpack Language Models
authors: Sun Hao, Hewitt John
conference: "Arxiv"
year: 2023
bibkey: sun2023character
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12751"}
tags: ['Ethics And Bias', 'Interpretability And Explainability', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Tokenization', 'Transformer']
---
The Backpack is a Transformer alternative shown to improve interpretability in English language modeling by decomposing predictions into a weighted sum of token sense components. However Backpacks reliance on token45;defined meaning raises questions as to their potential for languages other than English a language for which subword tokenization provides a reasonable approximation for lexical items. In this work we train evaluate interpret and control Backpack language models in character45;tokenized Chinese in which words are often composed of many characters. We find that our (134M parameter) Chinese Backpack language model performs comparably to a (104M parameter) Transformer and learns rich character45;level meanings that log45;additively compose to form word meanings. In SimLex45;style lexical semantic evaluations simple averages of Backpack character senses outperform input embeddings from a Transformer. We find that complex multi45;character meanings are often formed by using the same per45;character sense weights consistently across context. Exploring interpretability45;through control we show that we can localize a source of gender bias in our Backpacks to specific character senses and intervene to reduce the bias.
