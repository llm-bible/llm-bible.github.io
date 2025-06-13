---
layout: publication
title: 'Unleashing Multi-hop Reasoning Potential In Large Language Models Through Repetition Of Misordered Context'
authors: Sangwon Yu, Ik-hwan Kim, Jongyoon Song, Saehyung Lee, Junsung Park, Sungroh Yoon
conference: "Arxiv"
year: 2024
bibkey: yu2024unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07103"}
tags: ['Prompting', 'Reinforcement Learning']
---
Multi-hop reasoning, which requires multi-step reasoning based on the
supporting documents within a given context, remains challenging for large
language models (LLMs). LLMs often struggle to filter out irrelevant documents
within the context, and their performance is sensitive to the absolute position
of supporting documents within that context. In this paper, we identify an
additional challenge: LLMs' performance is also sensitive to the order,
relative position, in which the supporting documents are presented. We refer to
this as the misordered context problem. To address this issue, based on the
theoretical approach, we propose a simple yet effective method called context
repetition (CoRe), which involves prompting the model by repeatedly presenting
the context. This ensures that certain contiguous reasoning segments within
supporting documents are presented in the optimal order, effectively guiding
the model's reasoning in the appropriate direction. Applying CoRe, we improve
the F1 score by up to 30%p on multi-hop QA tasks and increase accuracy by up to
70%p on a synthetic task. Additionally, CoRe helps mitigate the well-known
"lost-in-the-middle" problem in LLMs and can be effectively combined with
retrieval-based approaches utilizing Chain-of-Thought (CoT) reasoning.
