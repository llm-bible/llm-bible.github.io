---
layout: publication
title: 'Talk Before You Retrieve: Agent-led Discussions For Better RAG In Medical QA'
authors: Xuanzhao Dong, Wenhui Zhu, Hao Wang, Xiwen Chen, Peijie Qiu, Rui Yin, Yi Su, Yalin Wang
conference: "Arxiv"
year: 2025
bibkey: dong2025talk
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.21252'}
  - {name: "Code", url: 'https://github.com/LLM-VLM-GSL/Discuss-RAG'}
tags: ['Agentic', 'Has Code', 'RAG', 'Applications', 'Training Techniques']
---
Medical question answering (QA) is a reasoning-intensive task that remains
challenging for large language models (LLMs) due to hallucinations and outdated
domain knowledge. Retrieval-Augmented Generation (RAG) provides a promising
post-training solution by leveraging external knowledge. However, existing
medical RAG systems suffer from two key limitations: (1) a lack of modeling for
human-like reasoning behaviors during information retrieval, and (2) reliance
on suboptimal medical corpora, which often results in the retrieval of
irrelevant or noisy snippets. To overcome these challenges, we propose
Discuss-RAG, a plug-and-play module designed to enhance the medical QA RAG
system through collaborative agent-based reasoning. Our method introduces a
summarizer agent that orchestrates a team of medical experts to emulate
multi-turn brainstorming, thereby improving the relevance of retrieved content.
Additionally, a decision-making agent evaluates the retrieved snippets before
their final integration. Experimental results on four benchmark medical QA
datasets show that Discuss-RAG consistently outperforms MedRAG, especially
significantly improving answer accuracy by up to 16.67% on BioASQ and 12.20% on
PubMedQA. The code is available at: https://github.com/LLM-VLM-GSL/Discuss-RAG.
