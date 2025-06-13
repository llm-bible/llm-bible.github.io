---
layout: publication
title: 'Rethinking Data: Towards Better Performing Domain-specific Small Language Models'
authors: Boris Nazarov, Darya Frolova, Yackov Lubarsky, Alexei Gaissinski, Pavel Kisilev
conference: "IEEE Global Communications Conference GLOBECOM 2024 Workshop IMMLLM6G"
year: 2025
bibkey: nazarov2025rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01464"}
tags: ['Fine-Tuning', 'Applications', 'Merging', 'Training Techniques', 'Pretraining Methods']
---
Fine-tuning of Large Language Models (LLMs) for downstream tasks, performed
on domain-specific data has shown significant promise. However, commercial use
of such LLMs is limited by the high computational cost required for their
deployment at scale. On the other hand, small Language Models (LMs) are much
more cost effective but have subpar performance in a similar setup. This paper
presents our approach to finetuning a small LM, that reaches high accuracy in
multiple choice question answering task. We achieve this by improving data
quality at each stage of the LM training pipeline. In particular, we start with
data structuring resulting in extraction of compact, semantically meaningful
text chunks used by a retriever. This allows more efficient knowledge digestion
by the LM. Further, we improve the retrieved context by training a lightweight
Chunk Re-Ranker (CRR) that generates more accurate relative relevance chunk
scores. Finally, we improve the model generalization ability by merging the
models fine-tuned with different parameters on different data subsets. We
present detailed procedure descriptions, and corresponding experimental
findings that show the improvements of each one of the proposed techniques.
