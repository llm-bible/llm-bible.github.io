---
layout: publication
title: 'Fact Or Guesswork? Evaluating Large Language Model''s Medical Knowledge With Structured One-hop Judgment'
authors: Jiaxi Li, Yiwei Wang, Kai Zhang, Yujun Cai, Bryan Hooi, Nanyun Peng, Kai-wei Chang, Jin Lu
conference: "Arxiv"
year: 2025
bibkey: li2025fact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14275"}
tags: ['RAG', 'Applications', 'Reinforcement Learning']
---
Large language models (LLMs) have been widely adopted in various downstream
task domains. However, their ability to directly recall and apply factual
medical knowledge remains under-explored. Most existing medical QA benchmarks
assess complex reasoning or multi-hop inference, making it difficult to isolate
LLMs' inherent medical knowledge from their reasoning capabilities. Given the
high-stakes nature of medical applications, where incorrect information can
have critical consequences, it is essential to evaluate how well LLMs encode,
retain, and recall fundamental medical facts.
  To bridge this gap, we introduce the Medical Knowledge Judgment, a dataset
specifically designed to measure LLMs' one-hop factual medical knowledge. MKJ
is constructed from the Unified Medical Language System (UMLS), a large-scale
repository of standardized biomedical vocabularies and knowledge graphs. We
frame knowledge assessment as a binary judgment task, requiring LLMs to verify
the correctness of medical statements extracted from reliable and structured
knowledge sources.
  Our experiments reveal that LLMs struggle with factual medical knowledge
retention, exhibiting significant performance variance across different
semantic categories, particularly for rare medical conditions. Furthermore,
LLMs show poor calibration, often being overconfident in incorrect answers. To
mitigate these issues, we explore retrieval-augmented generation, demonstrating
its effectiveness in improving factual accuracy and reducing uncertainty in
medical decision-making.
