---
layout: publication
title: 'Lettucedetect: A Hallucination Detection Framework For RAG Applications'
authors: Ádám Kovács, Gábor Recski
conference: "Arxiv"
year: 2025
bibkey: kovács2025hallucination
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17125"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'BERT', 'Prompting']
---
Retrieval Augmented Generation (RAG) systems remain vulnerable to
hallucinated answers despite incorporating external knowledge sources. We
present LettuceDetect a framework that addresses two critical limitations in
existing hallucination detection methods: (1) the context window constraints of
traditional encoder-based methods, and (2) the computational inefficiency of
LLM based approaches. Building on ModernBERT's extended context capabilities
(up to 8k tokens) and trained on the RAGTruth benchmark dataset, our approach
outperforms all previous encoder-based models and most prompt-based models,
while being approximately 30 times smaller than the best models. LettuceDetect
is a token-classification model that processes context-question-answer triples,
allowing for the identification of unsupported claims at the token level.
Evaluations on the RAGTruth corpus demonstrate an F1 score of 79.22% for
example-level detection, which is a 14.8% improvement over Luna, the previous
state-of-the-art encoder-based architecture. Additionally, the system can
process 30 to 60 examples per second on a single GPU, making it more practical
for real-world RAG applications.
