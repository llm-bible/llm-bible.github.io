---
layout: publication
title: 'Ptt5-v2: A Closer Look At Continued Pretraining Of T5 Models For The Portuguese Language'
authors: Marcos Piau, Roberto Lotufo, Rodrigo Nogueira
conference: "Arxiv"
year: 2024
bibkey: piau2024closer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10806"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Pretraining Methods', 'Reinforcement Learning']
---
Despite advancements in Natural Language Processing (NLP) and the growing
availability of pretrained models, the English language remains the primary
focus of model development. Continued pretraining on language-specific corpora
provides a practical solution for adapting models to other languages. However,
the impact of different pretraining settings on downstream tasks remains
underexplored. This work introduces \\(\texttt\{ptt5-v2\}\\), investigating the
continued pretraining of T5 models for Portuguese. We first develop a baseline
set of settings and pretrain models with sizes up to 3B parameters. Finetuning
on three Portuguese downstream tasks (assin2 STS, assin2 RTE, and TweetSentBR)
yields SOTA results on the latter two. We then explore the effects of different
pretraining configurations, including pretraining data quality, optimization
strategies, and multi-epoch pretraining. Perhaps surprisingly, their impact
remains subtle compared to our baseline. We release \\(\texttt\{ptt5-v2\}\\)
pretrained checkpoints and their MonoT5-based finetuned \\(\texttt\{MonoPTT5\}\\)
rerankers on HuggingFace in their respective collections at
\url\{https://huggingface.co/unicamp-dl\}.
