---
layout: publication
title: 'Visual-rag: Benchmarking Text-to-image Retrieval Augmented Generation For Visual Knowledge Intensive Queries'
authors: Yin Wu, Quanyu Long, Jing Li, Jianfei Yu, Wenya Wang
conference: "Arxiv"
year: 2025
bibkey: wu2025visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16636"}
tags: ['RAG', 'Applications', 'Multimodal Models']
---
Retrieval-Augmented Generation (RAG) is a popular approach for enhancing
Large Language Models (LLMs) by addressing their limitations in verifying facts
and answering knowledge-intensive questions. As the research in LLM extends
their capability to handle input modality other than text, e.g. image, several
multimodal RAG benchmarks are proposed. Nonetheless, they mainly use textual
knowledge bases as the primary source of evidences for augmentation. There
still lack benchmarks designed to evaluate images as augmentation in RAG
systems and how they leverage visual knowledge. We propose Visual-RAG, a novel
Question Answering benchmark that emphasizes visual knowledge intensive
questions. Unlike prior works relying on text-based evidence, Visual-RAG
necessitates text-to-image retrieval and integration of relevant clue images to
extract visual knowledge as evidence. With Visual-RAG, we evaluate 5
open-sourced and 3 proprietary Multimodal LLMs (MLLMs), revealing that images
can serve as good evidence in RAG; however, even the SoTA models struggle with
effectively extracting and utilizing visual knowledge
