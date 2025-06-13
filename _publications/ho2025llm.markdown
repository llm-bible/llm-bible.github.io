---
layout: publication
title: 'Llm-as-a-judge: Reassessing The Performance Of Llms In Extractive QA'
authors: Xanh Ho, Jiahao Huang, Florian Boudin, Akiko Aizawa
conference: "Arxiv"
year: 2025
bibkey: ho2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11972"}
tags: ['Ethics and Bias', 'Applications']
---
Extractive reading comprehension question answering (QA) datasets are
typically evaluated using Exact Match (EM) and F1-score, but these metrics
often fail to fully capture model performance. With the success of large
language models (LLMs), they have been employed in various tasks, including
serving as judges (LLM-as-a-judge). In this paper, we reassess the performance
of QA models using LLM-as-a-judge across four reading comprehension QA
datasets. We examine different families of LLMs and various answer types to
evaluate the effectiveness of LLM-as-a-judge in these tasks. Our results show
that LLM-as-a-judge is highly correlated with human judgments and can replace
traditional EM/F1 metrics. By using LLM-as-a-judge, the correlation with human
judgments improves significantly, from 0.22 (EM) and 0.40 (F1-score) to 0.85.
These findings confirm that EM and F1 metrics underestimate the true
performance of the QA models. While LLM-as-a-judge is not perfect for more
difficult answer types (e.g., job), it still outperforms EM/F1, and we observe
no bias issues, such as self-preference, when the same model is used for both
the QA and judgment tasks.
