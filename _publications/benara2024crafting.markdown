---
layout: publication
title: Crafting Interpretable Embeddings by Asking LLMs Questions
authors: Benara Vinamra, Singh Chandan, Morris John X., Antonello Richard, Stoica Ion, Huth Alexander G., Gao Jianfeng
conference: "Arxiv"
year: 2024
bibkey: benara2024crafting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16714"}
tags: ['ARXIV', 'Applications', 'Interpretability And Interpretability', 'LLM', 'NLP', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) have rapidly improved text embeddings for a growing array of natural-language processing tasks. However their opaqueness and proliferation into scientific domains such as neuroscience have created a growing need for interpretability. Here we ask whether we can obtain interpretable embeddings through LLM prompting. We introduce question-answering embeddings (QA-Emb) embeddings where each feature represents an answer to a yes/no question asked to an LLM. Training QA-Emb reduces to selecting a set of underlying questions rather than learning model weights. We use QA-Emb to flexibly generate interpretable models for predicting fMRI voxel responses to language stimuli. QA-Emb significantly outperforms an established interpretable baseline and does so while requiring very few questions. This paves the way towards building flexible feature spaces that can concretize and evaluate our understanding of semantic brain representations. We additionally find that QA-Emb can be effectively approximated with an efficient model and we explore broader applications in simple NLP tasks.
