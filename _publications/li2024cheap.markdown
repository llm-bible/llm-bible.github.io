---
layout: publication
title: 'PEDANTS: Cheap But Effective And Interpretable Answer Equivalence'
authors: Zongxia Li, Ishani Mondal, Yijun Liang, Huy Nghiem, Jordan Lee Boyd-graber
conference: "Empirical Methods in Natural Language Processing 2024"
year: 2024
bibkey: li2024cheap
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.11161'}
tags: ['BERT', 'Applications', 'Model Architecture']
---
Question answering (QA) can only make progress if we know if an answer is
correct, but current answer correctness (AC) metrics struggle with verbose,
free-form answers from large language models (LLMs). There are two challenges
with current short-form QA evaluations: a lack of diverse styles of evaluation
data and an over-reliance on expensive and slow LLMs. LLM-based scorers
correlate better with humans, but this expensive task has only been tested on
limited QA datasets. We rectify these issues by providing rubrics and datasets
for evaluating machine QA adopted from the Trivia community. We also propose an
efficient, and interpretable QA evaluation that is more stable than an exact
match and neural methods(BERTScore).
