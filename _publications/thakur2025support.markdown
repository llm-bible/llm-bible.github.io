---
layout: publication
title: 'Support Evaluation For The TREC 2024 RAG Track: Comparing Human Versus LLM Judges'
authors: Nandan Thakur, Ronak Pradeep, Shivani Upadhyay, Daniel Campos, Nick Craswell, Jimmy Lin
conference: "Arxiv"
year: 2025
bibkey: thakur2025support
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15205"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Ethics and Bias']
---
Retrieval-augmented generation (RAG) enables large language models (LLMs) to
generate answers with citations from source documents containing "ground
truth", thereby reducing system hallucinations. A crucial factor in RAG
evaluation is "support", whether the information in the cited documents
supports the answer. To this end, we conducted a large-scale comparative study
of 45 participant submissions on 36 topics to the TREC 2024 RAG Track,
comparing an automatic LLM judge (GPT-4o) against human judges for support
assessment. We considered two conditions: (1) fully manual assessments from
scratch and (2) manual assessments with post-editing of LLM predictions. Our
results indicate that for 56% of the manual from-scratch assessments, human and
GPT-4o predictions match perfectly (on a three-level scale), increasing to 72%
in the manual with post-editing condition. Furthermore, by carefully analyzing
the disagreements in an unbiased study, we found that an independent human
judge correlates better with GPT-4o than a human judge, suggesting that LLM
judges can be a reliable alternative for support assessment. To conclude, we
provide a qualitative analysis of human and GPT-4o errors to help guide future
iterations of support assessment.
