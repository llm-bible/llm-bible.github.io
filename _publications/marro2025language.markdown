---
layout: publication
title: 'Language Models Are Implicitly Continuous'
authors: Samuele Marro, Davide Evangelista, X. Angelo Huang, Emanuele La Malfa, Michele Lombardi, Michael Wooldridge
conference: "Arxiv"
year: 2025
bibkey: marro2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03933"}
tags: ['Pretraining Methods', 'Model Architecture', 'Transformer']
---
Language is typically modelled with discrete sequences. However, the most
successful approaches to language modelling, namely neural networks, are
continuous and smooth function approximators. In this work, we show that
Transformer-based language models implicitly learn to represent sentences as
continuous-time functions defined over a continuous input space. This
phenomenon occurs in most state-of-the-art Large Language Models (LLMs),
including Llama2, Llama3, Phi3, Gemma, Gemma2, and Mistral, and suggests that
LLMs reason about language in ways that fundamentally differ from humans. Our
work formally extends Transformers to capture the nuances of time and space
continuity in both input and output space. Our results challenge the
traditional interpretation of how LLMs understand language, with several
linguistic and engineering implications.
