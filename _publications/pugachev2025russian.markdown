---
layout: publication
title: 'REPA: Russian Error Types Annotation For Evaluating Text Generation And Judgment Capabilities'
authors: Alexander Pugachev, Alena Fenogenova, Vladislav Mikhailov, Ekaterina Artemova
conference: "Arxiv"
year: 2025
bibkey: pugachev2025russian
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13102"}
tags: ['Few-Shot', 'Tools', 'Language Modeling', 'Ethics and Bias', 'Applications']
---
Recent advances in large language models (LLMs) have introduced the novel
paradigm of using LLMs as judges, where an LLM evaluates and scores the outputs
of another LLM, which often correlates highly with human preferences. However,
the use of LLM-as-a-judge has been primarily studied in English. In this paper,
we evaluate this framework in Russian by introducing the Russian Error tyPes
Annotation dataset (REPA), a dataset of 1k user queries and 2k LLM-generated
responses. Human annotators labeled each response pair expressing their
preferences across ten specific error types, as well as selecting an overall
preference. We rank six generative LLMs across the error types using three
rating systems based on human preferences. We also evaluate responses using
eight LLM judges in zero-shot and few-shot settings. We describe the results of
analyzing the judges and position and length biases. Our findings reveal a
notable gap between LLM judge performance in Russian and English. However,
rankings based on human and LLM preferences show partial alignment, suggesting
that while current LLM judges struggle with fine-grained evaluation in Russian,
there is potential for improvement.
