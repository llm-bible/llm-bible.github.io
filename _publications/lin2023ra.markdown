---
layout: publication
title: 'RA-DIT: Retrieval-augmented Dual Instruction Tuning'
authors: Lin Xi Victoria, Chen Xilun, Chen Mingda, Shi Weijia, Lomeli Maria, James Rich, Rodriguez Pedro, Kahn Jacob, Szilvasy Gergely, Lewis Mike, Zettlemoyer Luke, Yih Scott
conference: "Arxiv"
year: 2023
bibkey: lin2023ra
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01352"}
tags: ['Few Shot', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Retrieval-augmented language models (RALMs) improve performance by accessing
long-tail and up-to-date knowledge from external data stores, but are
challenging to build. Existing approaches require either expensive
retrieval-specific modifications to LM pre-training or use post-hoc integration
of the data store that leads to suboptimal performance. We introduce
Retrieval-Augmented Dual Instruction Tuning (RA-DIT), a lightweight fine-tuning
methodology that provides a third option by retrofitting any LLM with retrieval
capabilities. Our approach operates in two distinct fine-tuning steps: (1) one
updates a pre-trained LM to better use retrieved information, while (2) the
other updates the retriever to return more relevant results, as preferred by
the LM. By fine-tuning over tasks that require both knowledge utilization and
contextual awareness, we demonstrate that each stage yields significant
performance improvements, and using both leads to additional gains. Our best
model, RA-DIT 65B, achieves state-of-the-art performance across a range of
knowledge-intensive zero- and few-shot learning benchmarks, significantly
outperforming existing in-context RALM approaches by up to +8.9% in 0-shot
setting and +1.4% in 5-shot setting on average.
