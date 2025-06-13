---
layout: publication
title: 'Tokenization Of Gaze Data'
authors: Tim Rolff, Jurik Karimian, Niklas Hypki, Susanne Schmidt, Markus Lappe, Frank Steinicke
conference: "Arxiv"
year: 2025
bibkey: rolff2025tokenization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22145"}
tags: ['Fine-Tuning', 'Training Techniques', 'Tokenization', 'Pretraining Methods', 'Multimodal Models']
---
A considerable part of the performance of today's large language models
(LLM's) and multimodal large language models (MLLM's) depends on their
tokenization strategies. While tokenizers are extensively researched for
textual and visual input, there is no research on tokenization strategies for
gaze data due to its nature. However, a corresponding tokenization strategy
would allow using the vision capabilities of pre-trained MLLM's for gaze data,
for example, through fine-tuning.
  In this paper, we aim to close this research gap by analyzing five different
tokenizers for gaze data on three different datasets for the forecasting and
generation of gaze data through LLMs (cf.~\cref\{fig:teaser\}). We evaluate the
tokenizers regarding their reconstruction and compression abilities. Further,
we train an LLM for each tokenization strategy, measuring its generative and
predictive performance. Overall, we found that a quantile tokenizer outperforms
all others in predicting the gaze positions and k-means is best when predicting
gaze velocities.
