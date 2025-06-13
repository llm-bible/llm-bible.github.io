---
layout: publication
title: 'Trans-tokenization And Cross-lingual Vocabulary Transfers: Language Adaptation Of Llms For Low-resource NLP'
authors: François Remy, Pieter Delobelle, Hayastan Avetisyan, Alfiya Khabibullina, Miryam De Lhoneux, Thomas Demeester
conference: "Arxiv"
year: 2024
bibkey: remy2024trans
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04303"}
tags: ['Applications', 'RAG', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques', 'Tokenization']
---
The development of monolingual language models for low and mid-resource
languages continues to be hindered by the difficulty in sourcing high-quality
training data. In this study, we present a novel cross-lingual vocabulary
transfer strategy, trans-tokenization, designed to tackle this challenge and
enable more efficient language adaptation. Our approach focuses on adapting a
high-resource monolingual LLM to an unseen target language by initializing the
token embeddings of the target language using a weighted average of
semantically similar token embeddings from the source language. For this, we
leverage a translation resource covering both the source and target languages.
We validate our method with the Tweeties, a series of trans-tokenized LLMs, and
demonstrate their competitive performance on various downstream tasks across a
small but diverse set of languages. Additionally, we introduce Hydra LLMs,
models with multiple swappable language modeling heads and embedding tables,
which further extend the capabilities of our trans-tokenization strategy. By
designing a Hydra LLM based on the multilingual model TowerInstruct, we
developed a state-of-the-art machine translation model for Tatar, in a
zero-shot manner, completely bypassing the need for high-quality parallel data.
This breakthrough is particularly significant for low-resource languages like
Tatar, where high-quality parallel data is hard to come by. By lowering the
data and time requirements for training high-quality models, our
trans-tokenization strategy allows for the development of LLMs for a wider
range of languages, especially those with limited resources. We hope that our
work will inspire further research and collaboration in the field of
cross-lingual vocabulary transfer and contribute to the empowerment of
languages on a global scale.
