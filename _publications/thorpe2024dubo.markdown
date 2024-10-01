---
layout: publication
title: 'Dubo-sql: Diverse Retrieval-augmented Generation And Fine Tuning For Text-to-sql'
authors: Thorpe Dayton G., Duberstein Andrew J., Kinsey Ian A.
conference: "Arxiv"
year: 2024
bibkey: thorpe2024dubo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12560"}
tags: ['GPT', 'Model Architecture', 'RAG']
---
"The current state-of-the-art (SOTA) for automated text-to-SQL still falls well short of expert human performance as measured by execution accuracy (EX) on the BIRD-SQL benchmark. The most accurate methods are also slow and expensive. To advance the SOTA for text-to-SQL while reducing cost and improving speed, we explore the combination of low-cost fine tuning, novel methods for diverse retrieval-augmented generation (RAG) and new input and output formats that help large language models (LLMs) achieve higher EX. We introduce two new methods, Dubo-SQL v1 and v2. Dubo-SQL v1 sets a new record for EX on the holdout test set of BIRD-SQL. Dubo-SQL v2 achieves even higher performance on the BIRD-SQL dev set. Dubo-SQL v1 relies on LLMs from OpenAI, but uses the low-cost GPT-3.5 Turbo while exceeding the performance of the next-best model using OpenAI, which instead uses the more expensive GPT-4. Dubo-SQL v1 exceeds the performance of the next-best model using GPT-3.5 by over 20&#37;. Dubo-SQL v2 uses GPT-4 Turbo and RAG in place of fine tuning to push EX higher."
