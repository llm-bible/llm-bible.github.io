---
layout: publication
title: Concept45;aware Data Construction Improves In45;context Learning Of Language Models
authors: Štefánik Michal, Kadlčík Marek, Sojka Petr
conference: "Arxiv"
year: 2024
bibkey: štefánik2024concept
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09703"}
tags: ['Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Many recent language models (LMs) are capable of in45;context learning (ICL) manifested in the LMs ability to perform a new task solely from natural45;language instruction. Previous work curating in45;context learners assumes that ICL emerges from a vast over45;parametrization or the scale of multi45;task training. However recent theoretical work attributes the ICL ability to concept45;dependent training data and creates functional in45;context learners even in small45;scale synthetic settings. In this work we practically explore this newly identified axis of ICL quality. We propose Concept45;aware Training (CoAT) a framework for constructing training scenarios that make it beneficial for the LM to learn to utilize the analogical reasoning concepts from demonstrations. We find that by using CoAT pre45;trained transformers can learn to better utilise new latent concepts from demonstrations and that such ability makes ICL more robust to the functional deficiencies of the previous models. Finally we show that concept45;aware in45;context learning is more effective for a majority of new tasks when compared to traditional instruction tuning resulting in a performance comparable to the previous in45;context learners using magnitudes of more training data.
