---
layout: publication
title: QUITO Accelerating Long45;context Reasoning Through Query45;guided Context Compression
authors: Wang Wenshan, Wang Yihang, Fan Yixing, Liao Huaming, Guo Jiafeng
conference: "Arxiv"
year: 2024
bibkey: wang2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.00274"}
  - {name: "Code", url: "https://github.com/Wenshansilvia/attention&#95;compressor"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Prompting', 'RAG']
---
In45;context learning (ICL) capabilities are foundational to the success of large language models (LLMs). Recently context compression has attracted growing interest since it can largely reduce reasoning complexities and computation costs of LLMs. In this paper we introduce a novel Query45;gUIded aTtention cOmpression (QUITO) method which leverages attention of the question over the contexts to filter useless information. Specifically we take a trigger token to calculate the attention distribution of the context in response to the question. Based on the distribution we propose three different filtering methods to satisfy the budget constraints of the context length. We evaluate the QUITO using two widely45;used datasets namely NaturalQuestions and ASQA. Experimental results demonstrate that QUITO significantly outperforms established baselines across various datasets and downstream LLMs underscoring its effectiveness. Our code is available at https://github.com/Wenshansilvia/attention&#95;compressor.
