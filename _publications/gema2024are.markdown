---
layout: publication
title: 'Are We Done With MMLU?'
authors: Gema Aryo Pradipta, Leang Joshua Ong Jun, Hong Giwon, Devoto Alessio, Mancino Alberto Carlo Maria, Saxena Rohit, He Xuanli, Zhao Yu, Du Xiaotang, Madani Mohammad Reza Ghasemi, Barale Claire, Mchardy Robert, Harris Joshua, Kaddour Jean, Van Krieken Emile, Minervini Pasquale
conference: "Arxiv"
year: 2024
bibkey: gema2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04127"}
  - {name: "Code", url: "https://huggingface.co/datasets/edinburgh-dawg/mmlu-redux"}
tags: ['Has Code', 'Tools', 'Uncategorized']
---
Maybe not. We identify and analyse errors in the popular Massive Multitask Language Understanding (MMLU) benchmark. Even though MMLU is widely adopted, our analysis demonstrates numerous ground truth errors that obscure the true capabilities of LLMs. For example, we find that 57&#37; of the analysed questions in the Virology subset contain errors. To address this issue, we introduce a comprehensive framework for identifying dataset errors using a novel error taxonomy. Then, we create MMLU-Redux, which is a subset of 3,000 manually re-annotated questions across 30 MMLU subjects. Using MMLU-Redux, we demonstrate significant discrepancies with the model performance metrics that were originally reported. Our results strongly advocate for revising MMLU's error-ridden questions to enhance its future utility and reliability as a benchmark. Therefore, we open up MMLU-Redux for additional annotation https://huggingface.co/datasets/edinburgh-dawg/mmlu-redux.
