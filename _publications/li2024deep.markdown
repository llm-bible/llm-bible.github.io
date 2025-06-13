---
layout: publication
title: 'DRS: Deep Question Reformulation With Structured Output'
authors: Zhecheng Li, Yiwei Wang, Bryan Hooi, Yujun Cai, Nanyun Peng, Kai-wei Chang
conference: "Arxiv"
year: 2024
bibkey: li2024deep
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.17993'}
tags: ['Reinforcement Learning', 'GPT', 'Applications', 'Model Architecture']
---
Question answering represents a core capability of large language models
(LLMs). However, when individuals encounter unfamiliar knowledge in texts, they
often formulate questions that the text itself cannot answer due to
insufficient understanding of the underlying information. Recent studies reveal
that while LLMs can detect unanswerable questions, they struggle to assist
users in reformulating these questions. Even advanced models like GPT-3.5
demonstrate limited effectiveness in this regard. To address this limitation,
we propose DRS: Deep Question Reformulation with Structured Output, a novel
zero-shot method aimed at enhancing LLMs ability to assist users in
reformulating questions to extract relevant information from new documents. DRS
combines the strengths of LLMs with a DFS-based algorithm to iteratively
explore potential entity combinations and constrain outputs using predefined
entities. This structured approach significantly enhances the reformulation
capabilities of LLMs. Comprehensive experimental evaluations demonstrate that
DRS improves the reformulation accuracy of GPT-3.5 from 23.03% to 70.42%, while
also enhancing the performance of open-source models, such as Gemma2-9B, from
26.35% to 56.75%.
