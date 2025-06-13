---
layout: publication
title: 'Llm-based Weak Supervision Framework For Query Intent Classification In Video Search'
authors: Farnoosh Javadi, Phanideep Gampa, Alyssa Woo, Xingxing Geng, Hang Zhang, Jose Sepulveda, Belhassen Bayar, Fei Wang
conference: "Arxiv"
year: 2024
bibkey: javadi2024llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.08931'}
tags: ['ACL', 'In-Context Learning', 'RAG', 'Training Techniques', 'Tools', 'Prompting', 'TACL']
---
Streaming services have reshaped how we discover and engage with digital
entertainment. Despite these advancements, effectively understanding the wide
spectrum of user search queries continues to pose a significant challenge. An
accurate query understanding system that can handle a variety of entities that
represent different user intents is essential for delivering an enhanced user
experience. We can build such a system by training a natural language
understanding (NLU) model; however, obtaining high-quality labeled training
data in this specialized domain is a substantial obstacle. Manual annotation is
costly and impractical for capturing users' vast vocabulary variations. To
address this, we introduce a novel approach that leverages large language
models (LLMs) through weak supervision to automatically annotate a vast
collection of user search queries. Using prompt engineering and a diverse set
of LLM personas, we generate training data that matches human annotator
expectations. By incorporating domain knowledge via Chain of Thought and
In-Context Learning, our approach leverages the labeled data to train
low-latency models optimized for real-time inference. Extensive evaluations
demonstrated that our approach outperformed the baseline with an average
relative gain of 113% in recall. Furthermore, our novel prompt engineering
framework yields higher quality LLM-generated data to be used for weak
supervision; we observed 47.60% improvement over baseline in agreement rate
between LLM predictions and human annotations with respect to F1 score,
weighted according to the distribution of occurrences of the search queries.
Our persona selection routing mechanism further adds an additional 3.67%
increase in weighted F1 score on top of our novel prompt engineering framework.
