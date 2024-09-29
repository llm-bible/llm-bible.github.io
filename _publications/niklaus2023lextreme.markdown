---
layout: publication
title: LEXTREME A Multi-Lingual and Multi-Task Benchmark for the Legal Domain
authors: Niklaus Joel, Matoshi Veton, Rani Pooja, Galassi Andrea, Stürmer Matthias, Chalkidis Ilias
conference: "EMNLP Findings"
year: 2023
bibkey: niklaus2023lextreme
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.13126"}
tags: ['Ethics And Bias', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Survey Paper', 'Transformer']
---
Lately propelled by the phenomenal advances around the transformer architecture the legal NLP field has enjoyed spectacular growth. To measure progress well curated and challenging benchmarks are crucial. However most benchmarks are English only and in legal NLP specifically there is no multilingual benchmark available yet. Additionally many benchmarks are saturated with the best models clearly outperforming the best humans and achieving near perfect scores. We survey the legal NLP literature and select 11 datasets covering 24 languages creating LEXTREME. To provide a fair comparison we propose two aggregate scores one based on the datasets and one on the languages. The best baseline (XLM-R large) achieves both a dataset aggregate score a language aggregate score of 61.3. This indicates that LEXTREME is still very challenging and leaves ample room for improvement. To make it easy for researchers and practitioners to use we release LEXTREME on huggingface together with all the code required to evaluate models and a public Weights and Biases project with all the runs.
