---
layout: publication
title: Dubo45;sql Diverse Retrieval45;augmented Generation And Fine Tuning For Text45;to45;sql
authors: Thorpe Dayton G., Duberstein Andrew J., Kinsey Ian A.
conference: "Arxiv"
year: 2024
bibkey: thorpe2024dubo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.12560"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG']
---
The current state45;of45;the45;art (SOTA) for automated text45;to45;SQL still falls well short of expert human performance as measured by execution accuracy (EX) on the BIRD45;SQL benchmark. The most accurate methods are also slow and expensive. To advance the SOTA for text45;to45;SQL while reducing cost and improving speed we explore the combination of low45;cost fine tuning novel methods for diverse retrieval45;augmented generation (RAG) and new input and output formats that help large language models (LLMs) achieve higher EX. We introduce two new methods Dubo45;SQL v1 and v2. Dubo45;SQL v1 sets a new record for EX on the holdout test set of BIRD45;SQL. Dubo45;SQL v2 achieves even higher performance on the BIRD45;SQL dev set. Dubo45;SQL v1 relies on LLMs from OpenAI but uses the low45;cost GPT45;3.5 Turbo while exceeding the performance of the next45;best model using OpenAI which instead uses the more expensive GPT45;4. Dubo45;SQL v1 exceeds the performance of the next45;best model using GPT45;3.5 by over 2037;. Dubo45;SQL v2 uses GPT45;4 Turbo and RAG in place of fine tuning to push EX higher.
