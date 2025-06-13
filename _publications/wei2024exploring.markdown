---
layout: publication
title: 'Cnnsum: Exploring Long-context Summarization With Large Language Models In Chinese Novels'
authors: Lingxiao Wei, He Yan, Xiangju Lu, Junmin Zhu, Jun Wang, Wei Zhang
conference: "Arxiv"
year: 2024
bibkey: wei2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.02819"}
  - {name: "Code", url: "https://github.com/CxsGhost/CNNSum)"}
tags: ['Fine-Tuning', 'Applications', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) have been well-researched in various long-context tasks. However, the scarcity of long-context summarization datasets hinders progress in this area. To address this, we introduce CNNSum, a multi-scale long-context summarization benchmark based on Chinese novels, featuring human-driven annotations across four subsets totaling 695 samples, with lengths ranging from 16k to 128k. We benchmark numerous LLMs and conduct detailed human assessments to summarize abnormal output types. Furthermore, we extensively explore how to improve long-context summarization. In our study: (1) Advanced LLMs may generate much subjective commentary, leading to vague summaries. (2) Currently, long-context summarization mainly relies on memory ability. The advantages of Large LLMs are hard to utilize, thus small LLMs are more cost-effective. (3) Different prompt types paired with various version models may cause large performance gaps. In further fine-tuning, these can be mitigated, and the Base version models perform better. (4) LLMs with RoPE-base scaled exhibit strong extrapolation potential; using short-context data can significantly improve long-context summarization performance. However, further applying other interpolation methods requires careful selection. (5) CNNSum provides more reliable evaluation results than other benchmarks. We release CNNSum to advance future research.(https://github.com/CxsGhost/CNNSum)
