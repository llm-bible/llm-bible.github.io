---
layout: publication
title: 'Conformalnl2ltl: Translating Natural Language Instructions Into Temporal Logic Formulas With Conformal Correctness Guarantees'
authors: Jun Wang, David Smith Sundarsingh, Jyotirmoy V. Deshmukh, Yiannis Kantaros
conference: "Arxiv"
year: 2025
bibkey: wang2025translating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.21022'}
tags: ['RAG']
---
Linear Temporal Logic (LTL) has become a prevalent specification language for
robotic tasks. To mitigate the significant manual effort and expertise required
to define LTL-encoded tasks, several methods have been proposed for translating
Natural Language (NL) instructions into LTL formulas, which, however, lack
correctness guarantees. To address this, we introduce a new NL-to-LTL
translation method, called ConformalNL2LTL, that can achieve user-defined
translation success rates over unseen NL commands. Our method constructs LTL
formulas iteratively by addressing a sequence of open-vocabulary
Question-Answering (QA) problems with LLMs. To enable uncertainty-aware
translation, we leverage conformal prediction (CP), a distribution-free
uncertainty quantification tool for black-box models. CP enables our method to
assess the uncertainty in LLM-generated answers, allowing it to proceed with
translation when sufficiently confident and request help otherwise. We provide
both theoretical and empirical results demonstrating that ConformalNL2LTL
achieves user-specified translation accuracy while minimizing help rates.
