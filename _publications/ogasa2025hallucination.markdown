---
layout: publication
title: 'Hallucination Detection Using Multi-view Attention Features'
authors: Yuya Ogasa, Yuki Arase
conference: "Arxiv"
year: 2025
bibkey: ogasa2025hallucination
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04335"}
tags: ['Transformer', 'Ethics and Bias', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods']
---
This study tackles token-level hallucination detection in outputs of large
language models. Previous studies revealed that attention exhibits irregular
patterns when hallucination occurs. Inspired by this, we extract features from
the attention matrix that provide complementary views of (a) the average
attention each token receives, which helps identify whether certain tokens are
overly influential or ignored, (b) the diversity of attention each token
receives, which reveals whether attention is biased toward specific subsets,
and (c) the diversity of tokens a token attends to during generation, which
indicates whether the model references a narrow or broad range of information.
These features are input to a Transformer-based classifier to conduct
token-level classification to identify hallucinated spans. Experimental results
indicate that the proposed method outperforms strong baselines on hallucination
detection with longer input contexts, i.e., data-to-text and summarization
tasks.
