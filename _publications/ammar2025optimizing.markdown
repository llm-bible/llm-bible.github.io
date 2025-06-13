---
layout: publication
title: 'Optimizing Retrieval-augmented Generation: Analysis Of Hyperparameter Impact On Performance And Efficiency'
authors: Adel Ammar, Anis Koubaa, Omer Nacar, Wadii Boulila
conference: "Arxiv"
year: 2025
bibkey: ammar2025optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.08445"}
tags: ['RAG', 'Applications', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Large language models achieve high task performance yet often hallucinate or rely on outdated knowledge. Retrieval-augmented generation (RAG) addresses these gaps by coupling generation with external search. We analyse how hyperparameters influence speed and quality in RAG systems, covering Chroma and Faiss vector stores, chunking policies, cross-encoder re-ranking, and temperature, and we evaluate six metrics: faithfulness, answer correctness, answer relevancy, context precision, context recall, and answer similarity. Chroma processes queries 13% faster, whereas Faiss yields higher retrieval precision, revealing a clear speed-accuracy trade-off. Naive fixed-length chunking with small windows and minimal overlap outperforms semantic segmentation while remaining the quickest option. Re-ranking provides modest gains in retrieval quality yet increases runtime by roughly a factor of 5, so its usefulness depends on latency constraints. These results help practitioners balance computational cost and accuracy when tuning RAG systems for transparent, up-to-date responses. Finally, we re-evaluate the top configurations with a corrective RAG workflow and show that their advantages persist when the model can iteratively request additional evidence. We obtain a near-perfect context precision (99%), which demonstrates that RAG systems can achieve extremely high retrieval accuracy with the right combination of hyperparameters, with significant implications for applications where retrieval quality directly impacts downstream task performance, such as clinical decision support in healthcare.
