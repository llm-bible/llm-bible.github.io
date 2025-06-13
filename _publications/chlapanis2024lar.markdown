---
layout: publication
title: 'LAR-ECHR: A New Legal Argument Reasoning Task And Dataset For Cases Of The European Court Of Human Rights'
authors: Odysseas S. Chlapanis, Dimitrios Galanis, Ion Androutsopoulos
conference: "Arxiv"
year: 2024
bibkey: chlapanis2024lar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13352"}
tags: ['GPT', 'Model Architecture', 'Reinforcement Learning']
---
We present Legal Argument Reasoning (LAR), a novel task designed to evaluate
the legal reasoning capabilities of Large Language Models (LLMs). The task
requires selecting the correct next statement (from multiple choice options) in
a chain of legal arguments from court proceedings, given the facts of the case.
We constructed a dataset (LAR-ECHR) for this task using cases from the European
Court of Human Rights (ECHR). We evaluated seven general-purpose LLMs on
LAR-ECHR and found that (a) the ranking of the models is aligned with that of
LegalBench, an established US-based legal reasoning benchmark, even though
LAR-ECHR is based on EU law, (b) LAR-ECHR distinguishes top models more
clearly, compared to LegalBench, (c) even the best model (GPT-4o) obtains 75.8%
accuracy on LAR-ECHR, indicating significant potential for further model
improvement. The process followed to construct LAR-ECHR can be replicated with
cases from other legal systems.
