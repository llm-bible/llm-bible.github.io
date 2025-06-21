---
layout: publication
title: Neural Machine Translation With Monolingual Translation Memory
authors: Deng Cai, Yan Wang, Huayang Li, Wai Lam, Lemao Liu
conference: Arxiv
year: 2021
citations: 28
bibkey: cai2021neural
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.11269'}]
tags: [RAG, Fine-Tuning]
---
Prior work has proved that Translation memory (TM) can boost the performance
of Neural Machine Translation (NMT). In contrast to existing work that uses
bilingual corpus as TM and employs source-side similarity search for memory
retrieval, we propose a new framework that uses monolingual memory and performs
learnable memory retrieval in a cross-lingual manner. Our framework has unique
advantages. First, the cross-lingual memory retriever allows abundant
monolingual data to be TM. Second, the memory retriever and NMT model can be
jointly optimized for the ultimate translation goal. Experiments show that the
proposed method obtains substantial improvements. Remarkably, it even
outperforms strong TM-augmented NMT baselines using bilingual TM. Owning to the
ability to leverage monolingual data, our model also demonstrates effectiveness
in low-resource and domain adaptation scenarios.