---
layout: publication
title: 'Predictive Prompt Analysis'
authors: Jae Yong Lee, Sungmin Kang, Shin Yoo
conference: "Arxiv"
year: 2025
bibkey: lee2025predictive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.18883'}
tags: ['Prompting', 'Training Techniques']
---
Large Language Models (LLMs) are machine learning models that have seen
widespread adoption due to their capability of handling previously difficult
tasks. LLMs, due to their training, are sensitive to how exactly a question is
presented, also known as prompting. However, prompting well is challenging, as
it has been difficult to uncover principles behind prompting -- generally,
trial-and-error is the most common way of improving prompts, despite its
significant computational cost. In this context, we argue it would be useful to
perform `predictive prompt analysis', in which an automated technique would
perform a quick analysis of a prompt and predict how the LLM would react to it,
relative to a goal provided by the user. As a demonstration of the concept, we
present Syntactic Prevalence Analyzer (SPA), a predictive prompt analysis
approach based on sparse autoencoders (SAEs). SPA accurately predicted how
often an LLM would generate target syntactic structures during code synthesis,
with up to 0.994 Pearson correlation between the predicted and actual
prevalence of the target structure. At the same time, SPA requires only 0.4%
of the time it takes to run the LLM on a benchmark. As LLMs are increasingly
used during and integrated into modern software development, our proposed
predictive prompt analysis concept has the potential to significantly ease the
use of LLMs for both practitioners and researchers.
