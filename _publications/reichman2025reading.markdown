---
layout: publication
title: 'Reading With Intent -- Neutralizing Intent'
authors: Benjamin Reichman, Adar Avsian, Larry Heck
conference: "Arxiv"
year: 2025
bibkey: reichman2025reading
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.03475'}
tags: ['RAG']
---
Queries to large language models (LLMs) can be divided into two parts: the
instruction/question and the accompanying context. The context for
retrieval-augmented generation (RAG) systems in most benchmarks comes from
Wikipedia or Wikipedia-like texts which are written in a neutral and factual
tone. However, when RAG systems retrieve internet-based content, they encounter
text with diverse tones and linguistic styles, introducing challenges for
downstream tasks. The Reading with Intent task addresses this issue by
evaluating how varying tones in context passages affect model performance.
Building on prior work that focused on sarcasm, we extend this paradigm by
constructing a dataset where context passages are transformed to \\(11\\) distinct
emotions using a better synthetic data generation approach. Using this dataset,
we train an emotion translation model to systematically adapt passages to
specified emotional tones. The human evaluation shows that the LLM fine-tuned
to become the emotion-translator benefited from the synthetically generated
data. Finally, the emotion-translator is used in the Reading with Intent task
to transform the passages to a neutral tone. By neutralizing the passages, it
mitigates the challenges posed by sarcastic passages and improves overall
results on this task by about \\(3%\\).
