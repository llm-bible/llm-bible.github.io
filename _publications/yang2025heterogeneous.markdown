---
layout: publication
title: 'Heterag: A Heterogeneous Retrieval-augmented Generation Framework With Decoupled Knowledge Representations'
authors: Peiru Yang, Xintian Li, Zhiyang Hu, Jiapeng Wang, Jinhua Yin, Huili Wang, Lizhi He, Shuai Yang, Shangguang Wang, Yongfeng Huang, Tao Qi
conference: "Arxiv"
year: 2025
bibkey: yang2025heterogeneous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10529"}
tags: ['Prompting', 'RAG', 'Efficiency and Optimization', 'Tools']
---
Retrieval-augmented generation (RAG) methods can enhance the performance of
LLMs by incorporating retrieved knowledge chunks into the generation process.
In general, the retrieval and generation steps usually have different
requirements for these knowledge chunks. The retrieval step benefits from
comprehensive information to improve retrieval accuracy, whereas excessively
long chunks may introduce redundant contextual information, thereby diminishing
both the effectiveness and efficiency of the generation process. However,
existing RAG methods typically employ identical representations of knowledge
chunks for both retrieval and generation, resulting in suboptimal performance.
In this paper, we propose a heterogeneous RAG framework (\myname) that
decouples the representations of knowledge chunks for retrieval and generation,
thereby enhancing the LLMs in both effectiveness and efficiency. Specifically,
we utilize short chunks to represent knowledge to adapt the generation step and
utilize the corresponding chunk with its contextual information from
multi-granular views to enhance retrieval accuracy. We further introduce an
adaptive prompt tuning method for the retrieval model to adapt the
heterogeneous retrieval augmented generation process. Extensive experiments
demonstrate that \myname achieves significant improvements compared to
baselines.
