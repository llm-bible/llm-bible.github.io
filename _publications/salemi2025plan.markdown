---
layout: publication
title: 'Plan-and-refine: Diverse And Comprehensive Retrieval-augmented Generation'
authors: Alireza Salemi, Chris Samarinas, Hamed Zamani
conference: "Arxiv"
year: 2025
bibkey: salemi2025plan
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07794"}
tags: ['Tools', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Applications']
---
This paper studies the limitations of (retrieval-augmented) large language
models (LLMs) in generating diverse and comprehensive responses, and introduces
the Plan-and-Refine (P&R) framework based on a two phase system design. In the
global exploration phase, P&R generates a diverse set of plans for the given
input, where each plan consists of a list of diverse query aspects with
corresponding additional descriptions. This phase is followed by a local
exploitation phase that generates a response proposal for the input query
conditioned on each plan and iteratively refines the proposal for improving the
proposal quality. Finally, a reward model is employed to select the proposal
with the highest factuality and coverage. We conduct our experiments based on
the ICAT evaluation methodology--a recent approach for answer factuality and
comprehensiveness evaluation. Experiments on the two diverse information
seeking benchmarks adopted from non-factoid question answering and TREC search
result diversification tasks demonstrate that P&R significantly outperforms
baselines, achieving up to a 13.1% improvement on the ANTIQUE dataset and a
15.41% improvement on the TREC dataset. Furthermore, a smaller scale user study
confirms the substantial efficacy of the P&R framework.
