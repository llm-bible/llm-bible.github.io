---
layout: publication
title: 'MQA-KEAL: Multi-hop Question Answering Under Knowledge Editing For Arabic Language'
authors: Muhammad Asif Ali, Nawal Daftardar, Mutayyaba Waheed, Jianbin Qin, Di Wang
conference: "Arxiv"
year: 2024
bibkey: ali2024mqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12257"}
tags: ['Applications']
---
Large Language Models (LLMs) have demonstrated significant capabilities
across numerous application domains. A key challenge is to keep these models
updated with latest available information, which limits the true potential of
these models for the end-applications. Although, there have been numerous
attempts for LLMs Knowledge Editing (KE), i.e., to edit the LLMs prior
knowledge and in turn test it via Multi-hop Question Answering (MQA), yet so
far these studies are primarily focused on English language. To bridge this
gap, in this paper we propose: Multi-hop Questioning Answering under Knowledge
Editing for Arabic Language (MQA-KEAL). MQA-KEAL stores knowledge edits as
structured knowledge units in the external memory. In order to solve multi-hop
question, it first uses task-decomposition to decompose the question into
smaller sub-problems. Later for each sub-problem, it iteratively queries the
external memory and/or target LLM in order to generate the final response. In
addition, we also contribute MQUAKE-AR (Arabic translation of English benchmark
MQUAKE), as well as a new benchmark MQA-AEVAL for rigorous performance
evaluation of MQA under KE for Arabic language. Experimentation evaluation
reveals MQA-KEAL outperforms the baseline models by a significant margin.
