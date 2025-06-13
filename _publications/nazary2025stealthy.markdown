---
layout: publication
title: 'Stealthy Llm-driven Data Poisoning Attacks Against Embedding-based Retrieval-augmented Recommender Systems'
authors: Fatemeh Nazary, Yashar Deldjoo, Tommaso Di Noia, Eugenio Di Sciascio
conference: "Arxiv"
year: 2025
bibkey: nazary2025stealthy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05196"}
tags: ['RAG', 'RecSys', 'Security']
---
We present a systematic study of provider-side data poisoning in
retrieval-augmented recommender systems (RAG-based). By modifying only a small
fraction of tokens within item descriptions -- for instance, adding emotional
keywords or borrowing phrases from semantically related items -- an attacker
can significantly promote or demote targeted items. We formalize these attacks
under token-edit and semantic-similarity constraints, and we examine their
effectiveness in both promotion (long-tail items) and demotion (short-head
items) scenarios. Our experiments on MovieLens, using two large language model
(LLM) retrieval modules, show that even subtle attacks shift final rankings and
item exposures while eluding naive detection. The results underscore the
vulnerability of RAG-based pipelines to small-scale metadata rewrites and
emphasize the need for robust textual consistency checks and provenance
tracking to thwart stealthy provider-side poisoning.
