---
layout: publication
title: 'Delta: An Online Document-level Translation Agent Based On Multi-level Memory'
authors: Yutong Wang, Jiali Zeng, Xuebo Liu, Derek F. Wong, Fandong Meng, Jie Zhou, Min Zhang
conference: "Published as a conference paper at ICLR 2025"
year: 2024
bibkey: wang2024online
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08143"}
  - {name: "Code", url: "https://github.com/YutongWang1216/DocMTAgent"}
tags: ['RAG', 'Agentic', 'Has Code', 'Applications']
---
Large language models (LLMs) have achieved reasonable quality improvements in
machine translation (MT). However, most current research on MT-LLMs still faces
significant challenges in maintaining translation consistency and accuracy when
processing entire documents. In this paper, we introduce DelTA, a
Document-levEL Translation Agent designed to overcome these limitations. DelTA
features a multi-level memory structure that stores information across various
granularities and spans, including Proper Noun Records, Bilingual Summary,
Long-Term Memory, and Short-Term Memory, which are continuously retrieved and
updated by auxiliary LLM-based components. Experimental results indicate that
DelTA significantly outperforms strong baselines in terms of translation
consistency and quality across four open/closed-source LLMs and two
representative document translation datasets, achieving an increase in
consistency scores by up to 4.58 percentage points and in COMET scores by up to
3.16 points on average. DelTA employs a sentence-by-sentence translation
strategy, ensuring no sentence omissions and offering a memory-efficient
solution compared to the mainstream method. Furthermore, DelTA improves pronoun
and context-dependent translation accuracy, and the summary component of the
agent also shows promise as a tool for query-based summarization tasks. The
code and data of our approach are released at
https://github.com/YutongWang1216/DocMTAgent.
