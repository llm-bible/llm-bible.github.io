---
layout: publication
title: Shapley Head Pruning Identifying and Removing Interference in Multilingual Transformers
authors: Held William, Yang Diyi
conference: "https://aclanthology.org/"
year: 2022
bibkey: held2022shapley
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.05709"}
tags: ['Model Architecture', 'Pruning', 'Transformer']
---
Multilingual transformer-based models demonstrate remarkable zero and few-shot transfer across languages by learning and reusing language-agnostic features. However as a fixed-size model acquires more languages its performance across all languages degrades a phenomenon termed interference. Often attributed to limited model capacity interference is commonly addressed by adding additional parameters despite evidence that transformer-based models are overparameterized. In this work we show that it is possible to reduce interference by instead identifying and pruning language-specific parameters. First we use Shapley Values a credit allocation metric from coalitional game theory to identify attention heads that introduce interference. Then we show that removing identified attention heads from a fixed model improves performance for a target language on both sentence classification and structural prediction seeing gains as large as 24.7. Finally we provide insights on language-agnostic and language-specific attention heads using attention visualization.
