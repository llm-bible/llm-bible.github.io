---
layout: publication
title: 'CDF-RAG: Causal Dynamic Feedback For Adaptive Retrieval-augmented Generation'
authors: Elahe Khatibi, Ziyu Wang, Amir M. Rahmani
conference: "Arxiv"
year: 2025
bibkey: khatibi2025cdf
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12560"}
  - {name: "Code", url: "https://github.com/"}
tags: ['Tools', 'RAG', 'Interpretability', 'Has Code', 'Interpretability and Explainability']
---
Retrieval-Augmented Generation (RAG) has significantly enhanced large
language models (LLMs) in knowledge-intensive tasks by incorporating external
knowledge retrieval. However, existing RAG frameworks primarily rely on
semantic similarity and correlation-driven retrieval, limiting their ability to
distinguish true causal relationships from spurious associations. This results
in responses that may be factually grounded but fail to establish
cause-and-effect mechanisms, leading to incomplete or misleading insights. To
address this issue, we introduce Causal Dynamic Feedback for Adaptive
Retrieval-Augmented Generation (CDF-RAG), a framework designed to improve
causal consistency, factual accuracy, and explainability in generative
reasoning. CDF-RAG iteratively refines queries, retrieves structured causal
graphs, and enables multi-hop causal reasoning across interconnected knowledge
sources. Additionally, it validates responses against causal pathways, ensuring
logically coherent and factually grounded outputs. We evaluate CDF-RAG on four
diverse datasets, demonstrating its ability to improve response accuracy and
causal correctness over existing RAG-based methods. Our code is publicly
available at https://github.com/ elakhatibi/CDF-RAG.
