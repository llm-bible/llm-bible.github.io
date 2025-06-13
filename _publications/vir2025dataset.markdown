---
layout: publication
title: 'PROMPTEVALS: A Dataset Of Assertions And Guardrails For Custom Production Large Language Model Pipelines'
authors: Reya Vir, Shreya Shankar, Harrison Chase, Will Fu-hinthorn, Aditya Parameswaran
conference: "Arxiv"
year: 2025
bibkey: vir2025dataset
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14738'}
tags: ['RAG', 'Model Architecture', 'Tools', 'Applications', 'GPT', 'Prompting']
---
Large language models (LLMs) are increasingly deployed in specialized
production data processing pipelines across diverse domains -- such as finance,
marketing, and e-commerce. However, when running them in production across many
inputs, they often fail to follow instructions or meet developer expectations.
To improve reliability in these applications, creating assertions or guardrails
for LLM outputs to run alongside the pipelines is essential. Yet, determining
the right set of assertions that capture developer requirements for a task is
challenging. In this paper, we introduce PROMPTEVALS, a dataset of 2087 LLM
pipeline prompts with 12623 corresponding assertion criteria, sourced from
developers using our open-source LLM pipeline tools. This dataset is 5x larger
than previous collections. Using a hold-out test split of PROMPTEVALS as a
benchmark, we evaluated closed- and open-source models in generating relevant
assertions. Notably, our fine-tuned Mistral and Llama 3 models outperform
GPT-4o by 20.93% on average, offering both reduced latency and improved
performance. We believe our dataset can spur further research in LLM
reliability, alignment, and prompt engineering.
