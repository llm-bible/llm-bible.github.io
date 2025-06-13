---
layout: publication
title: 'Compositional Generalization For Data-to-text Generation'
authors: Xinnuo Xu, Ivan Titov, Mirella Lapata
conference: "Findings of EMNLP 2023"
year: 2023
bibkey: xu2023compositional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02748"}
tags: ['RAG', 'Language Modeling', 'Applications']
---
Data-to-text generation involves transforming structured data, often
represented as predicate-argument tuples, into coherent textual descriptions.
Despite recent advances, systems still struggle when confronted with unseen
combinations of predicates, producing unfaithful descriptions (e.g.
hallucinations or omissions). We refer to this issue as compositional
generalisation, and it encouraged us to create a benchmark for assessing the
performance of different approaches on this specific problem. Furthermore, we
propose a novel model that addresses compositional generalization by clustering
predicates into groups. Our model generates text in a sentence-by-sentence
manner, relying on one cluster of predicates at a time. This approach
significantly outperforms T5~baselines across all evaluation metrics.Notably,
it achieved a 31% improvement over T5 in terms of a metric focused on
maintaining faithfulness to the input.
