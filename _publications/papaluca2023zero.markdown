---
layout: publication
title: 'Zero- And Few-shots Knowledge Graph Triplet Extraction With Large Language Models'
authors: Andrea Papaluca, Daniel Krefl, Sergio Mendez Rodriguez, Artem Lensky, Hanna Suominen
conference: "Arxiv"
year: 2023
bibkey: papaluca2023zero
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.01954'}
tags: ['Few-Shot', 'Prompting', 'Applications', 'Model Architecture']
---
In this work, we tested the Triplet Extraction (TE) capabilities of a variety
of Large Language Models (LLMs) of different sizes in the Zero- and Few-Shots
settings. In detail, we proposed a pipeline that dynamically gathers contextual
information from a Knowledge Base (KB), both in the form of context triplets
and of (sentence, triplets) pairs as examples, and provides it to the LLM
through a prompt. The additional context allowed the LLMs to be competitive
with all the older fully trained baselines based on the Bidirectional Long
Short-Term Memory (BiLSTM) Network architecture. We further conducted a
detailed analysis of the quality of the gathered KB context, finding it to be
strongly correlated with the final TE performance of the model. In contrast,
the size of the model appeared to only logarithmically improve the TE
capabilities of the LLMs.
