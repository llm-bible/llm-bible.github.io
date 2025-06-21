---
layout: publication
title: Teaching Language Models To Support Answers With Verified Quotes
authors: Jacob Menick et al.
conference: Arxiv
year: 2022
citations: 40
bibkey: menick2022teaching
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.11147'}]
tags: [Reinforcement Learning, Security, Agentic]
---
Recent large language models often answer factual questions correctly. But
users can't trust any given claim a model makes without fact-checking, because
language models can hallucinate convincing nonsense. In this work we use
reinforcement learning from human preferences (RLHP) to train "open-book" QA
models that generate answers whilst also citing specific evidence for their
claims, which aids in the appraisal of correctness. Supporting evidence is
drawn from multiple documents found via a search engine, or from a single
user-provided document. Our 280 billion parameter model, GopherCite, is able to
produce answers with high quality supporting evidence and abstain from
answering when unsure. We measure the performance of GopherCite by conducting
human evaluation of answers to questions in a subset of the NaturalQuestions
and ELI5 datasets. The model's response is found to be high-quality 80% of the
time on this Natural Questions subset, and 67% of the time on the ELI5 subset.
Abstaining from the third of questions for which it is most unsure improves
performance to 90% and 80% respectively, approaching human baselines.
However, analysis on the adversarial TruthfulQA dataset shows why citation is
only one part of an overall strategy for safety and trustworthiness: not all
claims supported by evidence are true.