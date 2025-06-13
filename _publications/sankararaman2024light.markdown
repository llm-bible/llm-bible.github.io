---
layout: publication
title: 'Provenance: A Light-weight Fact-checker For Retrieval Augmented LLM Generation Output'
authors: Hithesh Sankararaman, Mohammed Nasheed Yasin, Tanner Sorensen, Alessandro Di Bari, Andreas Stolcke
conference: "Proc. 2024 Conference on Empirical Methods in Natural Language Processing Industry Track pp. 1305-1313"
year: 2024
bibkey: sankararaman2024light
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01022"}
tags: ['Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
We present a light-weight approach for detecting nonfactual outputs from
retrieval-augmented generation (RAG). Given a context and putative output, we
compute a factuality score that can be thresholded to yield a binary decision
to check the results of LLM-based question-answering, summarization, or other
systems. Unlike factuality checkers that themselves rely on LLMs, we use
compact, open-source natural language inference (NLI) models that yield a
freely accessible solution with low latency and low cost at run-time, and no
need for LLM fine-tuning. The approach also enables downstream mitigation and
correction of hallucinations, by tracing them back to specific context chunks.
Our experiments show high area under the ROC curve (AUC) across a wide range of
relevant open source datasets, indicating the effectiveness of our method for
fact-checking RAG output.
