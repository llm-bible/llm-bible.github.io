---
layout: publication
title: 'Enhancing Multi-modal And Multi-hop Question Answering Via Structured Knowledge And Unified Retrieval-generation'
authors: Qian Yang, Qian Chen, Wen Wang, Baotian Hu, Min Zhang
conference: "Arxiv"
year: 2022
bibkey: yang2022enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.08632"}
  - {name: "Code", url: "https://github.com/HITsz-TMG/SKURG"}
tags: ['Multimodal Models', 'Has Code', 'Applications', 'Merging']
---
Multi-modal multi-hop question answering involves answering a question by
reasoning over multiple input sources from different modalities. Existing
methods often retrieve evidences separately and then use a language model to
generate an answer based on the retrieved evidences, and thus do not adequately
connect candidates and are unable to model the interdependent relations during
retrieval. Moreover, the pipelined approaches of retrieval and generation might
result in poor generation performance when retrieval performance is low. To
address these issues, we propose a Structured Knowledge and Unified
Retrieval-Generation (SKURG) approach. SKURG employs an Entity-centered Fusion
Encoder to align sources from different modalities using shared entities. It
then uses a unified Retrieval-Generation Decoder to integrate intermediate
retrieval results for answer generation and also adaptively determine the
number of retrieval steps. Extensive experiments on two representative
multi-modal multi-hop QA datasets MultimodalQA and WebQA demonstrate that SKURG
outperforms the state-of-the-art models in both source retrieval and answer
generation performance with fewer parameters. Our code is available at
https://github.com/HITsz-TMG/SKURG.
