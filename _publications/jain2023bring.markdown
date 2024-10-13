---
layout: publication
title: 'Bring Your Own Data! Self-supervised Evaluation For Large Language Models'
authors: Jain Neel, Saifullah Khalid, Wen Yuxin, Kirchenbauer John, Shu Manli, Saha Aniruddha, Goldblum Micah, Geiping Jonas, Goldstein Tom
conference: "Arxiv"
year: 2023
bibkey: jain2023bring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.13651"}
tags: ['Tokenization', 'Tools', 'Training Techniques', 'Uncategorized']
---
With the rise of Large Language Models (LLMs) and their ubiquitous deployment
in diverse domains, measuring language model behavior on realistic data is
imperative. For example, a company deploying a client-facing chatbot must
ensure that the model will not respond to client requests with profanity.
Current evaluations approach this problem using small, domain-specific datasets
with human-curated labels. These evaluation sets are often sampled from a
narrow and simplified distribution, and data sources can unknowingly be leaked
into the training set which can lead to misleading evaluations. To bypass these
drawbacks, we propose a framework for self-supervised evaluation of LLMs by
analyzing their sensitivity or invariance to transformations on the input text.
Self-supervised evaluation can directly monitor LLM behavior on datasets
collected in the wild or streamed during live model deployment. We demonstrate
self-supervised evaluation strategies for measuring closed-book knowledge,
toxicity, and long-range context dependence, in addition to sensitivity to
grammatical structure and tokenization errors. When comparisons to similar
human-labeled benchmarks are available, we find strong correlations between
self-supervised and human-supervised evaluations. The self-supervised paradigm
complements current evaluation strategies that rely on labeled data.
