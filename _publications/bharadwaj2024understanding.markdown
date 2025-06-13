---
layout: publication
title: 'Understanding Hidden Computations In Chain-of-thought Reasoning'
authors: Aryasomayajula Ram Bharadwaj
conference: "Arxiv"
year: 2024
bibkey: bharadwaj2024understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.04537'}
tags: ['Interpretability and Explainability', 'Transformer', 'Model Architecture', 'Prompting', 'Ethics and Bias', 'Interpretability', 'Pretraining Methods']
---
Chain-of-Thought (CoT) prompting has significantly enhanced the reasoning
abilities of large language models. However, recent studies have shown that
models can still perform complex reasoning tasks even when the CoT is replaced
with filler(hidden) characters (e.g., "..."), leaving open questions about how
models internally process and represent reasoning steps. In this paper, we
investigate methods to decode these hidden characters in transformer models
trained with filler CoT sequences. By analyzing layer-wise representations
using the logit lens method and examining token rankings, we demonstrate that
the hidden characters can be recovered without loss of performance. Our
findings provide insights into the internal mechanisms of transformer models
and open avenues for improving interpretability and transparency in language
model reasoning.
