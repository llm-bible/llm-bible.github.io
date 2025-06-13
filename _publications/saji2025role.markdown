---
layout: publication
title: 'Romanlens: The Role Of Latent Romanization In Multilinguality In Llms'
authors: Alan Saji, Jaavid Aktar Husain, Thanmay Jayakumar, Raj Dabre, Anoop Kunchukuttan, Ratish Puduppully
conference: "Arxiv"
year: 2025
bibkey: saji2025role
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.07424'}
tags: ['Reinforcement Learning', 'Interpretability and Explainability']
---
Large Language Models (LLMs) exhibit remarkable multilingual generalization
despite being predominantly trained on English-centric corpora. A fundamental
question arises: how do LLMs achieve such robust multilingual capabilities? We
take the case of non-Roman script languages, we investigate the role of
Romanization - the representation of non-Roman scripts using Roman characters -
as a bridge in multilingual processing. Using mechanistic interpretability
techniques, we analyze next-token generation and find that intermediate layers
frequently represent target words in Romanized form before transitioning to
native script, a phenomenon we term Latent Romanization. Further, through
activation patching experiments, we demonstrate that LLMs encode semantic
concepts similarly across native and Romanized scripts, suggesting a shared
underlying representation. Additionally, for translation into non-Roman script
languages, our findings reveal that when the target language is in Romanized
form, its representations emerge earlier in the model's layers compared to
native script. These insights contribute to a deeper understanding of
multilingual representation in LLMs and highlight the implicit role of
Romanization in facilitating language transfer.
