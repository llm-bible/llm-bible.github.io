---
layout: publication
title: Studying Large Language Model Behaviors Under Realistic Knowledge Conflicts
authors: Kortukov Evgenii, Rubinstein Alexander, Nguyen Elisa, Oh Seong Joon
conference: "Arxiv"
year: 2024
bibkey: kortukov2024studying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16032"}
  - {name: "Code", url: "https://github.com/kortukov/realistic\_knowledge\_conflicts/"}
tags: ['Ethics And Bias', 'Has Code', 'RAG', 'Tools']
---
Retrieval-augmented generation (RAG) mitigates many problems of fully parametric language models such as temporal degradation hallucinations and lack of grounding. In RAG the models knowledge can be updated from documents provided in context. This leads to cases of conflict between the models parametric knowledge and the contextual information where the model may not always update its knowledge. Previous work studied knowledge conflicts by creating synthetic documents that contradict the models correct parametric answers. We present a framework for studying knowledge conflicts in a realistic setup. We update incorrect parametric knowledge using real conflicting documents. This reflects how knowledge conflicts arise in practice. In this realistic scenario we find that knowledge updates fail less often than previously reported. In cases where the models still fail to update their answers we find a parametric bias the incorrect parametric answer appearing in context makes the knowledge update likelier to fail. These results suggest that the factual parametric knowledge of LLMs can negatively influence their reading abilities and behaviors. Our code is available at https://github.com/kortukov/realistic\_knowledge\_conflicts/.
