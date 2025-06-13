---
layout: publication
title: 'Proverbeval: Exploring LLM Evaluation Challenges For Low-resource Language Understanding'
authors: Israel Abebe Azime, Atnafu Lambebo Tonja, Tadesse Destaw Belay, Yonas Chanie, Bontu Fufa Balcha, Negasi Haile Abadi, Henok Biadglign Ademtew, Mulubrhan Abebe Nerea, Debela Desalegn Yadeta, Derartu Dagne Geremew, Assefa Atsbiha Tesfau, Philipp Slusallek, Thamar Solorio, Dietrich Klakow
conference: "Arxiv"
year: 2024
bibkey: azime2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05049"}
  - {name: "Code", url: "https://huggingface.co/datasets/israel/ProverbEval,"}
  - {name: "Code", url: "https://github.com/EthioNLP/EthioProverbEval"}
tags: ['Model Architecture', 'Tools', 'Has Code', 'Prompting', 'Attention Mechanism']
---
With the rapid development of evaluation datasets to assess LLMs
understanding across a wide range of subjects and domains, identifying a
suitable language understanding benchmark has become increasingly challenging.
In this work, we explore LLM evaluation challenges for low-resource language
understanding and introduce \proverbeval, LLM evaluation benchmark for
low-resource languages, focusing on low-resource language understanding in
culture-specific scenarios. We benchmark various LLMs and explore factors that
create variability in the benchmarking process. We observed performance
variances of up to 50%, depending on the order in which answer choices were
presented in multiple-choice tasks. Native language proverb descriptions
significantly improve tasks such as proverb generation, contributing to
improved outcomes. Additionally, monolingual evaluations consistently
outperformed their cross-lingual counterparts in generation tasks. We argue
that special attention must be given to the order of choices, the choice of
prompt language, task variability, and generation tasks when creating LLM
evaluation benchmarks. Evaluation data available at
https://huggingface.co/datasets/israel/ProverbEval, evaluation code
https://github.com/EthioNLP/EthioProverbEval.
