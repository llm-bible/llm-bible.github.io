---
layout: publication
title: 'Multi-ophthalingua: A Multilingual Benchmark For Assessing And Debiasing LLM Ophthalmological QA In Lmics'
authors: David Restrepo, Chenwei Wu, Zhengxu Tang, Zitao Shuai, Thao Nguyen Minh Phan, Jun-en Ding, Cong-tinh Dao, Jack Gallifant, Robyn Gayle Dychiao, Jose Carlo Artiaga, André Hiroshi Bando, Carolina Pelegrini Barbosa Gracitelli, Vincenz Ferrer, Leo Anthony Celi, Danielle Bitterman, Michael G Morley, Luis Filipe Nakayama
conference: "Arxiv"
year: 2024
bibkey: restrepo2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14304"}
tags: ['RAG', 'Agentic', 'Bias Mitigation', 'Ethics and Bias']
---
Current ophthalmology clinical workflows are plagued by over-referrals, long
waits, and complex and heterogeneous medical records. Large language models
(LLMs) present a promising solution to automate various procedures such as
triaging, preliminary tests like visual acuity assessment, and report
summaries. However, LLMs have demonstrated significantly varied performance
across different languages in natural language question-answering tasks,
potentially exacerbating healthcare disparities in Low and Middle-Income
Countries (LMICs). This study introduces the first multilingual
ophthalmological question-answering benchmark with manually curated questions
parallel across languages, allowing for direct cross-lingual comparisons. Our
evaluation of 6 popular LLMs across 7 different languages reveals substantial
bias across different languages, highlighting risks for clinical deployment of
LLMs in LMICs. Existing debiasing methods such as Translation Chain-of-Thought
or Retrieval-augmented generation (RAG) by themselves fall short of closing
this performance gap, often failing to improve performance across all languages
and lacking specificity for the medical domain. To address this issue, We
propose CLARA (Cross-Lingual Reflective Agentic system), a novel inference time
de-biasing method leveraging retrieval augmented generation and
self-verification. Our approach not only improves performance across all
languages but also significantly reduces the multilingual bias gap,
facilitating equitable LLM application across the globe.
