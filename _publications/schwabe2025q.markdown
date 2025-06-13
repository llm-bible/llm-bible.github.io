---
layout: publication
title: 'Q-NL Verifier: Leveraging Synthetic Data For Robust Knowledge Graph Question Answering'
authors: Tim Schwabe, Louisa Siebel, Patrik Valach, Maribel Acosta
conference: "Arxiv"
year: 2025
bibkey: schwabe2025q
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.01385'}
tags: ['RAG', 'Applications']
---
Question answering (QA) requires accurately aligning user questions with
structured queries, a process often limited by the scarcity of high-quality
query-natural language (Q-NL) pairs. To overcome this, we present Q-NL
Verifier, an approach to generating high-quality synthetic pairs of queries and
NL translations. Our approach relies on large language models (LLMs) to
generate semantically precise natural language paraphrases of structured
queries. Building on these synthetic Q-NL pairs, we introduce a learned
verifier component that automatically determines whether a generated paraphrase
is semantically equivalent to the original query. Our experiments with the
well-known LC-QuAD 2.0 benchmark show that Q-NL Verifier generalizes well to
paraphrases from other models and even human-authored translations. Our
approach strongly aligns with human judgments across varying query complexities
and outperforms existing NLP metrics in assessing semantic correctness. We also
integrate the verifier into QA pipelines, showing that verifier-filtered
synthetic data has significantly higher quality in terms of translation
correctness and enhances NL to Q translation accuracy. Lastly, we release an
updated version of the LC-QuAD 2.0 benchmark containing our synthetic Q-NL
pairs and verifier scores, offering a new resource for robust and scalable QA.
