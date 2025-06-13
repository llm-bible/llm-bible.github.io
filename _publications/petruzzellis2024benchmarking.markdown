---
layout: publication
title: 'Benchmarking GPT-4 On Algorithmic Problems: A Systematic Evaluation Of Prompting Strategies'
authors: Flavio Petruzzellis, Alberto Testolin, Alessandro Sperduti
conference: "Arxiv"
year: 2024
bibkey: petruzzellis2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17396"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Transformer', 'Prompting']
---
Large Language Models (LLMs) have revolutionized the field of Natural
Language Processing thanks to their ability to reuse knowledge acquired on
massive text corpora on a wide variety of downstream tasks, with minimal (if
any) tuning steps. At the same time, it has been repeatedly shown that LLMs
lack systematic generalization, which allows to extrapolate the learned
statistical regularities outside the training distribution. In this work, we
offer a systematic benchmarking of GPT-4, one of the most advanced LLMs
available, on three algorithmic tasks characterized by the possibility to
control the problem difficulty with two parameters. We compare the performance
of GPT-4 with that of its predecessor (GPT-3.5) and with a variant of the
Transformer-Encoder architecture recently introduced to solve similar tasks,
the Neural Data Router. We find that the deployment of advanced prompting
techniques allows GPT-4 to reach superior accuracy on all tasks, demonstrating
that state-of-the-art LLMs constitute a very strong baseline also in
challenging tasks that require systematic generalization.
