---
layout: publication
title: 'Identifying Non-replicable Social Science Studies With Language Models'
authors: Denitsa Saynova, Kajsa Hansson, Bastiaan Bruinsma, Annika Fredén, Moa Johansson
conference: "Arxiv"
year: 2025
bibkey: saynova2025identifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.10671'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'GPT', 'Model Architecture']
---
In this study, we investigate whether LLMs can be used to indicate if a study
in the behavioural social sciences is replicable. Using a dataset of 14
previously replicated studies (9 successful, 5 unsuccessful), we evaluate the
ability of both open-source (Llama 3 8B, Qwen 2 7B, Mistral 7B) and proprietary
(GPT-4o) instruction-tuned LLMs to discriminate between replicable and
non-replicable findings. We use LLMs to generate synthetic samples of responses
from behavioural studies and estimate whether the measured effects support the
original findings. When compared with human replication results for these
studies, we achieve F1 values of up to \\(77%\\) with Mistral 7B, \\(67%\\) with
GPT-4o and Llama 3 8B, and \\(55%\\) with Qwen 2 7B, suggesting their potential
for this task. We also analyse how effect size calculations are affected by
sampling temperature and find that low variance (due to temperature) leads to
biased effect estimates.
