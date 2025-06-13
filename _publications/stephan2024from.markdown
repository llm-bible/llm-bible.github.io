---
layout: publication
title: 'From Calculation To Adjudication: Examining LLM Judges On Mathematical Reasoning Tasks'
authors: Andreas Stephan, Dawei Zhu, Matthias Aßenmacher, Xiaoyu Shen, Benjamin Roth
conference: "Arxiv"
year: 2024
bibkey: stephan2024from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04168"}
tags: ['RAG', 'Applications']
---
To reduce the need for human annotations, large language models (LLMs) have been proposed as judges of the quality of other candidate models. The performance of LLM judges is typically evaluated by measuring the correlation with human judgments on generative tasks such as summarization or machine translation. In contrast, we study LLM judges on mathematical reasoning tasks. These tasks require multi-step reasoning, and the correctness of their solutions is verifiable, enabling a more objective evaluation. We perform a detailed performance analysis and find that easy samples are easy to judge, and difficult samples are difficult to judge. Our analysis uncovers a strong correlation between judgment performance and the candidate model task performance, indicating that judges tend to favor higher-quality models even if their answer is incorrect. As a consequence, we test whether we can predict the behavior of LLM judges using simple features such as part-of-speech tags and find that we can correctly predict 70%-75% of judgments. We conclude this study by analyzing practical use cases, showing that LLM judges consistently detect the on-average better model but largely fail if we use them to improve task performance.
