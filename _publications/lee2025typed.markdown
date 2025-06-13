---
layout: publication
title: 'Typed-rag: Type-aware Multi-aspect Decomposition For Non-factoid Question Answering'
authors: Donggeon Lee, Ahjeong Park, Hyeri Lee, Hyeonseo Nam, Yunho Maeng
conference: "Arxiv"
year: 2025
bibkey: lee2025typed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.15879"}
  - {name: "Code", url: "https://github.com/TeamNLP/Typed-RAG"}
tags: ['RAG', 'Applications', 'Has Code', 'Tools']
---
Non-factoid question-answering (NFQA) poses a significant challenge due to
its open-ended nature, diverse intents, and the need for multi-aspect
reasoning, which renders conventional factoid QA approaches, including
retrieval-augmented generation (RAG), inadequate. Unlike factoid questions,
non-factoid questions (NFQs) lack definitive answers and require synthesizing
information from multiple sources across various reasoning dimensions. To
address these limitations, we introduce Typed-RAG, a type-aware multi-aspect
decomposition framework within the RAG paradigm for NFQA. Typed-RAG classifies
NFQs into distinct types -- such as debate, experience, and comparison -- and
applies aspect-based decomposition to refine retrieval and generation
strategies. By decomposing multi-aspect NFQs into single-aspect sub-queries and
aggregating the results, Typed-RAG generates more informative and contextually
relevant responses. To evaluate Typed-RAG, we introduce Wiki-NFQA, a benchmark
dataset covering diverse NFQ types. Experimental results demonstrate that
Typed-RAG outperforms baselines, thereby highlighting the importance of
type-aware decomposition for effective retrieval and generation in NFQA. Our
code and dataset are available at https://github.com/TeamNLP/Typed-RAG.
