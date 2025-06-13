---
layout: publication
title: 'Enhancing Embedding Performance Through Large Language Model-based Text Enrichment And Rewriting'
authors: Nicholas Harris, Anand Butani, Syed Hashmy
conference: "Arxiv"
year: 2024
bibkey: harris2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.12283'}
tags: ['RAG', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Embedding models are crucial for various natural language processing tasks
but can be limited by factors such as limited vocabulary, lack of context, and
grammatical errors. This paper proposes a novel approach to improve embedding
performance by leveraging large language models (LLMs) to enrich and rewrite
input text before the embedding process. By utilizing ChatGPT 3.5 to provide
additional context, correct inaccuracies, and incorporate metadata, the
proposed method aims to enhance the utility and accuracy of embedding models.
The effectiveness of this approach is evaluated on three datasets:
Banking77Classification, TwitterSemEval 2015, and Amazon Counter-factual
Classification. Results demonstrate significant improvements over the baseline
model on the TwitterSemEval 2015 dataset, with the best-performing prompt
achieving a score of 85.34 compared to the previous best of 81.52 on the
Massive Text Embedding Benchmark (MTEB) Leaderboard. However, performance on
the other two datasets was less impressive, highlighting the importance of
considering domain-specific characteristics. The findings suggest that
LLM-based text enrichment has shown promising results to improve embedding
performance, particularly in certain domains. Hence, numerous limitations in
the process of embedding can be avoided.
