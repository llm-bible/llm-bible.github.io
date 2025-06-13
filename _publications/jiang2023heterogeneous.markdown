---
layout: publication
title: 'Chameleon: A Heterogeneous And Disaggregated Accelerator System For Retrieval-augmented Language Models'
authors: Wenqi Jiang, Marco Zeller, Roger Waleffe, Torsten Hoefler, Gustavo Alonso
conference: "Arxiv"
year: 2023
bibkey: jiang2023heterogeneous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09949"}
tags: ['RAG', 'Model Architecture']
---
A Retrieval-Augmented Language Model (RALM) combines a large language model
(LLM) with a vector database to retrieve context-specific knowledge during text
generation. This strategy facilitates impressive generation quality even with
smaller models, thus reducing computational demands by orders of magnitude. To
serve RALMs efficiently and flexibly, we propose Chameleon, a heterogeneous
accelerator system integrating both LLM and vector search accelerators in a
disaggregated architecture. The heterogeneity ensures efficient serving for
both inference and retrieval, while the disaggregation allows independent
scaling of LLM and vector search accelerators to fulfill diverse RALM
requirements. Our Chameleon prototype implements vector search accelerators on
FPGAs and assigns LLM inference to GPUs, with CPUs as cluster coordinators.
Evaluated on various RALMs, Chameleon exhibits up to 2.16\\(\times\\) reduction in
latency and 3.18x speedup in throughput compared to the hybrid CPU-GPU
architecture. The promising results pave the way for adopting heterogeneous
accelerators for not only LLM inference but also vector search in future RALM
systems.
