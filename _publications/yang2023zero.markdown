---
layout: publication
title: Zero-shot Query Reformulation For Conversational Search
authors: Yang Dayu, Zhang Yue, Fang Hui
conference: "Arxiv"
year: 2023
bibkey: yang2023zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.09384"}
tags: ['Applications', 'Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'Tools']
---
As the popularity of voice assistants continues to surge conversational search has gained increased attention in Information Retrieval. However data sparsity issues in conversational search significantly hinder the progress of supervised conversational search methods. Consequently researchers are focusing more on zero-shot conversational search approaches. Nevertheless existing zero-shot methods face three primary limitations they are not universally applicable to all retrievers their effectiveness lacks sufficient explainability and they struggle to resolve common conversational ambiguities caused by omission. To address these limitations we introduce a novel Zero-shot Query Reformulation (ZeQR) framework that reformulates queries based on previous dialogue contexts without requiring supervision from conversational search data. Specifically our framework utilizes language models designed for machine reading comprehension tasks to explicitly resolve two common ambiguities coreference and omission in raw queries. In comparison to existing zero-shot methods our approach is universally applicable to any retriever without additional adaptation or indexing. It also provides greater explainability and effectively enhances query intent understanding because ambiguities are explicitly and proactively resolved. Through extensive experiments on four TREC conversational datasets we demonstrate the effectiveness of our method which consistently outperforms state-of-the-art baselines.
