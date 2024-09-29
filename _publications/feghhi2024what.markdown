---
layout: publication
title: What Are Large Language Models Mapping To In The Brain A Case Against Over45;reliance On Brain Scores
authors: Feghhi Ebrahim, Hadidi Nima, Song Bryan, Blank Idan A., Kao Jonathan C.
conference: "Arxiv"
year: 2024
bibkey: feghhi2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01538"}
tags: ['Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Given the remarkable capabilities of large language models (LLMs) there has been a growing interest in evaluating their similarity to the human brain. One approach towards quantifying this similarity is by measuring how well a model predicts neural signals also called brain score. Internal representations from LLMs achieve state45;of45;the45;art brain scores leading to speculation that they share computational principles with human language processing. This inference is only valid if the subset of neural activity predicted by LLMs reflects core elements of language processing. Here we question this assumption by analyzing three neural datasets used in an impactful study on LLM45;to45;brain mappings with a particular focus on an fMRI dataset where participants read short passages. We first find that when using shuffled train45;test splits as done in previous studies with these datasets a trivial feature that encodes temporal autocorrelation not only outperforms LLMs but also accounts for the majority of neural variance that LLMs explain. We therefore use contiguous splits moving forward. Second we explain the surprisingly high brain scores of untrained LLMs by showing they do not account for additional neural variance beyond two simple features sentence length and sentence position. This undermines evidence used to claim that the transformer architecture biases computations to be more brain45;like. Third we find that brain scores of trained LLMs on this dataset can largely be explained by sentence length position and pronoun45;dereferenced static word embeddings; a small additional amount is explained by sense45;specific embeddings and contextual representations of sentence structure. We conclude that over45;reliance on brain scores can lead to over45;interpretations of similarity between LLMs and brains and emphasize the importance of deconstructing what LLMs are mapping to in neural signals.
