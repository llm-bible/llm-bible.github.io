---
layout: publication
title: 'MILU: A Multi-task Indic Language Understanding Benchmark'
authors: Sshubam Verma, Mohammed Safi Ur Rahman Khan, Vishwajeet Kumar, Rudra Murthy, Jaydeep Sen
conference: "Arxiv"
year: 2024
bibkey: verma2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02538"}
tags: ['RAG', 'Model Architecture', 'GPT', 'Reinforcement Learning']
---
Evaluating Large Language Models (LLMs) in low-resource and linguistically
diverse languages remains a significant challenge in NLP, particularly for
languages using non-Latin scripts like those spoken in India. Existing
benchmarks predominantly focus on English, leaving substantial gaps in
assessing LLM capabilities in these languages. We introduce MILU, a Multi task
Indic Language Understanding Benchmark, a comprehensive evaluation benchmark
designed to address this gap. MILU spans 8 domains and 41 subjects across 11
Indic languages, reflecting both general and culturally specific knowledge.
With an India-centric design, incorporates material from regional and
state-level examinations, covering topics such as local history, arts,
festivals, and laws, alongside standard subjects like science and mathematics.
We evaluate over 42 LLMs, and find that current LLMs struggle with MILU, with
GPT-4o achieving the highest average accuracy at 74 percent. Open multilingual
models outperform language-specific fine-tuned models, which perform only
slightly better than random baselines. Models also perform better in high
resource languages as compared to low resource ones. Domain-wise analysis
indicates that models perform poorly in culturally relevant areas like Arts and
Humanities, Law and Governance compared to general fields like STEM. To the
best of our knowledge, MILU is the first of its kind benchmark focused on Indic
languages, serving as a crucial step towards comprehensive cultural evaluation.
All code, benchmarks, and artifacts are publicly available to foster open
research.
