---
layout: publication
title: 'ER-RAG: Enhance RAG With Er-based Unified Modeling Of Heterogeneous Data Sources'
authors: Yikuan Xia, Jiazun Chen, Yirui Zhan, Suifeng Zhao, Weipeng Jiang, Chaorui Zhang, Wei Han, Bo Bai, Jun Gao
conference: "Arxiv"
year: 2025
bibkey: xia2025er
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.06271'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Multimodal Models', 'KDD', 'Pretraining Methods']
---
Large language models (LLMs) excel in question-answering (QA) tasks, and
retrieval-augmented generation (RAG) enhances their precision by incorporating
external evidence from diverse sources like web pages, databases, and knowledge
graphs. However, current RAG methods rely on agent-specific strategies for
individual data sources, posing challenges low-resource or black-box
environments and complicates operations when evidence is fragmented across
sources. To address these limitations, we propose ER-RAG, a framework that
unifies evidence integration across heterogeneous data sources using the
Entity-Relationship (ER) model. ER-RAG standardizes entity retrieval and
relationship querying through ER-based APIs with GET and JOIN operations. It
employs a two-stage generation process: first, a preference optimization module
selects optimal sources; second, another module constructs API chains based on
source schemas. This unified approach allows efficient fine-tuning and seamless
integration across diverse data sources. ER-RAG demonstrated its effectiveness
by winning all three tracks of the 2024 KDDCup CRAG Challenge, achieving
performance on par with commercial RAG pipelines using an 8B LLM backbone. It
outperformed hybrid competitors by 3.1% in LLM score and accelerated retrieval
by 5.5X.
