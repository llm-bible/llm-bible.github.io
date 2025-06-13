---
layout: publication
title: 'Bridging The Semantic Gaps: Improving Medical VQA Consistency With Llm-augmented Question Sets'
authors: Yongpei Ma, Pengyu Wang, Adam Dunn, Usman Naseem, Jinman Kim
conference: "Arxiv"
year: 2025
bibkey: ma2025bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11777"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Medical Visual Question Answering (MVQA) systems can interpret medical images
in response to natural language queries. However, linguistic variability in
question phrasing often undermines the consistency of these systems. To address
this challenge, we propose a Semantically Equivalent Question Augmentation
(SEQA) framework, which leverages large language models (LLMs) to generate
diverse yet semantically equivalent rephrasings of questions. Specifically,
this approach enriches linguistic diversity while preserving semantic meaning.
We further introduce an evaluation metric, Total Agreement Rate with
Semantically Equivalent Input and Correct Answer (TAR-SC), which assesses a
model's capability to generate consistent and correct responses to semantically
equivalent linguistic variations. In addition, we also propose three other
diversity metrics - average number of QA items per image (ANQI), average number
of questions per image with the same answer (ANQA), and average number of
open-ended questions per image with the same semantics (ANQS). Using the SEQA
framework, we augmented the benchmarked MVQA public datasets of SLAKE, VQA-RAD,
and PathVQA. As a result, all three datasets achieved significant improvements
by incorporating more semantically equivalent questions: ANQI increased by an
average of 86.1, ANQA by 85.1, and ANQS by 46. Subsequent experiments evaluate
three MVQA models (M2I2, MUMC, and BiomedGPT) under both zero-shot and
fine-tuning settings on the enhanced datasets. Experimental results in MVQA
datasets show that fine-tuned models achieve an average accuracy improvement of
19.35%, while our proposed TAR-SC metric shows an average improvement of 11.
61%, indicating a substantial enhancement in model consistency.
