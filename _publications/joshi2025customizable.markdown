---
layout: publication
title: 'Coke: Customizable Fine-grained Story Evaluation Via Chain-of-keyword Rationalization'
authors: Brihi Joshi, Sriram Venkatapathy, Mohit Bansal, Nanyun Peng, Haw-shiuan Chang
conference: "Arxiv"
year: 2025
bibkey: joshi2025customizable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.17136'}
tags: ['GPT', 'Interpretability and Explainability', 'Model Architecture']
---
Evaluating creative text such as human-written stories using language models
has always been a challenging task -- owing to the subjectivity of
multi-annotator ratings. To mimic the thinking process of humans, chain of
thought (CoT) generates free-text explanations that help guide a model's
predictions and Self-Consistency (SC) marginalizes predictions over multiple
generated explanations. In this study, we discover that the widely-used
self-consistency reasoning methods cause suboptimal results due to an objective
mismatch between generating 'fluent-looking' explanations vs. actually leading
to a good rating prediction for an aspect of a story. To overcome this
challenge, we propose \\(\textbf\{C\}\\)hain-\\(\textbf\{o\}\\)f-\\(\textbf\{Ke\}\\)ywords
(CoKe), that generates a sequence of keywords \\(\textit\{before\}\\) generating a
free-text rationale, that guide the rating prediction of our evaluation
language model. Then, we generate a diverse set of such keywords, and aggregate
the scores corresponding to these generations. On the StoryER dataset, CoKe
based on our small fine-tuned evaluation models not only reach human-level
performance and significantly outperform GPT-4 with a 2x boost in correlation
with human annotators, but also requires drastically less number of parameters.
