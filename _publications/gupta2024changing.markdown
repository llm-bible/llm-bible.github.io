---
layout: publication
title: 'Changing Answer Order Can Decrease MMLU Accuracy'
authors: Vipul Gupta, David Pantoja, Candace Ross, Adina Williams, Megan Ung
conference: "Arxiv"
year: 2024
bibkey: gupta2024changing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19470"}
tags: ['RAG', 'Security', 'Applications']
---
As large language models (LLMs) have grown in prevalence, particular
benchmarks have become essential for the evaluation of these models and for
understanding model capabilities. Most commonly, we use test accuracy averaged
across multiple subtasks in order to rank models on leaderboards, to determine
which model is best for our purposes. In this paper, we investigate the
robustness of the accuracy measurement on a widely used multiple choice
question answering dataset, MMLU. When shuffling the answer label contents, we
find that all explored models decrease in accuracy on MMLU, but not every model
is equally sensitive. These findings suggest a possible adjustment to the
standard practice of leaderboard testing, where we additionally consider the
percentage of examples each model answers correctly by random chance.
