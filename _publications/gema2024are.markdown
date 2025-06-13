---
layout: publication
title: 'Are We Done With MMLU?'
authors: Aryo Pradipta Gema, Joshua Ong Jun Leang, Giwon Hong, Alessio Devoto, Alberto Carlo Maria Mancino, Rohit Saxena, Xuanli He, Yu Zhao, Xiaotang Du, Mohammad Reza Ghasemi Madani, Claire Barale, Robert Mchardy, Joshua Harris, Jean Kaddour, Emile Van Krieken, Pasquale Minervini
conference: "Arxiv"
year: 2024
bibkey: gema2024are
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.04127'}
  - {name: "Code", url: 'https://huggingface.co/datasets/edinburgh-dawg/mmlu-redux-2.0'}
tags: ['Has Code', 'Tools']
---
Maybe not. We identify and analyse errors in the popular Massive Multitask
Language Understanding (MMLU) benchmark. Even though MMLU is widely adopted,
our analysis demonstrates numerous ground truth errors that obscure the true
capabilities of LLMs. For example, we find that 57% of the analysed questions
in the Virology subset contain errors. To address this issue, we introduce a
comprehensive framework for identifying dataset errors using a novel error
annotation protocol. Then, we create MMLU-Redux, which is a subset of 5,700
manually re-annotated questions across all 57 MMLU subjects. We estimate that
6.49% of MMLU questions contain errors. Using MMLU-Redux, we demonstrate
significant discrepancies with the model performance metrics that were
originally reported. Our results strongly advocate for revising MMLU's
error-ridden questions to enhance its future utility and reliability as a
benchmark. https://huggingface.co/datasets/edinburgh-dawg/mmlu-redux-2.0.
