---
layout: publication
title: 'Beyond Public Access In LLM Pre-training Data'
authors: Sruly Rosenblat, Tim O'reilly, Ilan Strauss
conference: "Arxiv"
year: 2025
bibkey: rosenblat2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00020"}
tags: ['Pre-Training', 'GPT', 'Tools', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Interpretability', 'Security', 'Training Techniques']
---
Using a legally obtained dataset of 34 copyrighted O'Reilly Media books, we
apply the DE-COP membership inference attack method to investigate whether
OpenAI's large language models were trained on copyrighted content without
consent. Our AUROC scores show that GPT-4o, OpenAI's more recent and capable
model, demonstrates strong recognition of paywalled O'Reilly book content
(AUROC = 82%), compared to OpenAI's earlier model GPT-3.5 Turbo. In contrast,
GPT-3.5 Turbo shows greater relative recognition of publicly accessible
O'Reilly book samples. GPT-4o Mini, as a much smaller model, shows no knowledge
of public or non-public O'Reilly Media content when tested (AUROC \\(\approx\\)
50%). Testing multiple models, with the same cutoff date, helps us account for
potential language shifts over time that might bias our findings. These results
highlight the urgent need for increased corporate transparency regarding
pre-training data sources as a means to develop formal licensing frameworks for
AI content training
