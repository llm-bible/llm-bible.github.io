---
layout: publication
title: FRACTAL Fine45;grained Scoring From Aggregate Text Labels
authors: Makhija Yukti, Agrawal Priyanka, Saket Rishi, Raghuveer Aravindan
conference: "Arxiv"
year: 2024
bibkey: makhija2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04817"}
tags: ['Applications', 'Efficiency And Optimization', 'RAG', 'Training Techniques']
---
Large language models (LLMs) are being increasingly tuned to power complex generation tasks such as writing fact45;seeking querying and reasoning. Traditionally human or model feedback for evaluating and further tuning LLM performance has been provided at the response level enabling faster and more cost45;effective assessments. However recent works (Amplayo et al. 2022 Wu et al. 2023) indicate that sentence45;level labels may provide more accurate and interpretable feedback for LLM optimization. In this work we introduce methods to disaggregate response45;level labels into sentence45;level (pseudo45;)labels. Our approach leverages multiple instance learning (MIL) and learning from label proportions (LLP) techniques in conjunction with prior information (e.g. document45;sentence cosine similarity) to train a specialized model for sentence45;level scoring. We also employ techniques which use model predictions to pseudo45;label the train45;set at the sentence45;level for model training to further improve performance. We conduct extensive evaluations of our methods across six datasets and four tasks retrieval question answering summarization and math reasoning. Our results demonstrate improved performance compared to multiple baselines across most of these tasks. Our work is the first to develop response45;level feedback to sentence45;level scoring techniques leveraging sentence45;level prior information along with comprehensive evaluations on multiple tasks as well as end45;to45;end finetuning evaluation showing performance comparable to a model trained on fine45;grained human annotated labels.
