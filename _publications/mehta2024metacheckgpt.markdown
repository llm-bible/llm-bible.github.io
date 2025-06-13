---
layout: publication
title: 'Metacheckgpt -- A Multi-task Hallucination Detector Using LLM Uncertainty And Meta-models'
authors: Rahul Mehta, Andrew Hoblitzell, Jack O'keefe, Hyeju Jang, Vasudeva Varma
conference: "Arxiv"
year: 2024
bibkey: mehta2024metacheckgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06948"}
tags: ['Transformer', 'Tools', 'GPT', 'Model Architecture', 'Pretraining Methods']
---
Hallucinations in large language models (LLMs) have recently become a
significant problem. A recent effort in this direction is a shared task at
Semeval 2024 Task 6, SHROOM, a Shared-task on Hallucinations and Related
Observable Overgeneration Mistakes. This paper describes our winning solution
ranked 1st and 2nd in the 2 sub-tasks of model agnostic and model aware tracks
respectively. We propose a meta-regressor framework of LLMs for model
evaluation and integration that achieves the highest scores on the leaderboard.
We also experiment with various transformer-based models and black box methods
like ChatGPT, Vectara, and others. In addition, we perform an error analysis
comparing GPT4 against our best model which shows the limitations of the
former.
