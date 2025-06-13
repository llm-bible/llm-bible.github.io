---
layout: publication
title: 'UCSC At Semeval-2025 Task 3: Context, Models And Prompt Optimization For Automated Hallucination Detection In LLM Output'
authors: Sicong Huang, Jincheng He, Shiyuan Huang, Karthik Raja Anandan, Arkajyoti Chakraborty, Ian Lane
conference: "Arxiv"
year: 2025
bibkey: huang2025ucsc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03030"}
tags: ['RAG', 'Tools', 'Efficiency and Optimization', 'Prompting']
---
Hallucinations pose a significant challenge for large language models when
answering knowledge-intensive queries. As LLMs become more widely adopted, it
is crucial not only to detect if hallucinations occur but also to pinpoint
exactly where in the LLM output they occur. SemEval 2025 Task 3, Mu-SHROOM:
Multilingual Shared-task on Hallucinations and Related Observable
Overgeneration Mistakes, is a recent effort in this direction. This paper
describes the UCSC system submission to the shared Mu-SHROOM task. We introduce
a framework that first retrieves relevant context, next identifies false
content from the answer, and finally maps them back to spans in the LLM output.
The process is further enhanced by automatically optimizing prompts. Our system
achieves the highest overall performance, ranking #1 in average position across
all languages. We release our code and experiment results.
