---
layout: publication
title: 'Likelihood-based Mitigation Of Evaluation Bias In Large Language Models'
authors: Ohi Masanari, Kaneko Masahiro, Koike Ryuto, Loem Mengsay, Okazaki Naoaki
conference: "Arxiv"
year: 2024
bibkey: ohi2024likelihood
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15987"}
tags: ['Ethics And Bias', 'Few Shot', 'In Context Learning', 'Prompting']
---
Large Language Models (LLMs) are widely used to evaluate natural language generation tasks as automated metrics. However, the likelihood, a measure of LLM's plausibility for a sentence, can vary due to superficial differences in sentences, such as word order and sentence structure. It is therefore possible that there might be a likelihood bias if LLMs are used for evaluation: they might overrate sentences with higher likelihoods while underrating those with lower likelihoods. In this paper, we investigate the presence and impact of likelihood bias in LLM-based evaluators. We also propose a method to mitigate the likelihood bias. Our method utilizes highly biased instances as few-shot examples for in-context learning. Our experiments in evaluating the data-to-text and grammatical error correction tasks reveal that several LLMs we test display a likelihood bias. Furthermore, our proposed method successfully mitigates this bias, also improving evaluation performance (in terms of correlation of models with human scores) significantly.
