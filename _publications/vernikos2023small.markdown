---
layout: publication
title: Small Language Models Improve Giants By Rewriting Their Outputs
authors: Vernikos Giorgos, Bražinskas Arthur, Adamek Jakub, Mallinson Jonathan, Severyn Aliaksei, Malmi Eric
conference: "Arxiv"
year: 2023
bibkey: vernikos2023small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13514"}
tags: ['Prompting', 'RAG', 'Security', 'Training Techniques']
---
Despite the impressive performance of large language models (LLMs) they often lag behind specialized models in various tasks. LLMs only use a fraction of the existing training data for in45;context learning while task45;specific models harness the full dataset for fine45;tuning. In this work we tackle the problem of leveraging training data to improve the performance of LLMs without fine45;tuning. Our approach directly targets LLM predictions without requiring access to their weights. We create a pool of candidates from the LLM through few45;shot prompting and we employ a compact model the LM45;corrector (LMCor) specifically trained to merge these candidates to produce an enhanced output. Our experiments on four natural language generation tasks demonstrate that even a small LMCor model (250M) substantially improves the few45;shot performance of LLMs (62B) matching and even outperforming standard fine45;tuning. Furthermore we illustrate the robustness of LMCor against different prompts thereby minimizing the need for extensive prompt engineering. Finally we show that LMCor can be seamlessly integrated with different LLMs at inference serving as a plug45;and45;play module to improve their performance.
