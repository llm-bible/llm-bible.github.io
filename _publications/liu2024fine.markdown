---
layout: publication
title: 'Fine-grained Guidance For Retrievers: Leveraging Llms'' Feedback In Retrieval-augmented Generation'
authors: Yuhang Liu, Xueyu Hu, Shengyu Zhang, Jingyuan Chen, Fan Wu, Fei Wu
conference: "Arxiv"
year: 2024
bibkey: liu2024fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.03957'}
tags: ['Reinforcement Learning', 'RAG', 'Efficiency and Optimization', 'Tools']
---
Retrieval-Augmented Generation (RAG) has proven to be an effective method for
mitigating hallucination issues inherent in large language models (LLMs).
Previous approaches typically train retrievers based on semantic similarity,
lacking optimization for RAG. More recent works have proposed aligning
retrievers with the preference signals of LLMs. However, these preference
signals are often difficult for dense retrievers, which typically have weaker
language capabilities, to understand and learn effectively. Drawing inspiration
from pedagogical theories like Guided Discovery Learning, we propose a novel
framework, FiGRet (Fine-grained Guidance for Retrievers), which leverages the
language capabilities of LLMs to construct examples from a more granular,
information-centric perspective to guide the learning of retrievers.
Specifically, our method utilizes LLMs to construct easy-to-understand examples
from samples where the retriever performs poorly, focusing on three learning
objectives highly relevant to the RAG scenario: relevance, comprehensiveness,
and purity. These examples serve as scaffolding to ultimately align the
retriever with the LLM's preferences. Furthermore, we employ a dual curriculum
learning strategy and leverage the reciprocal feedback between LLM and
retriever to further enhance the performance of the RAG system. A series of
experiments demonstrate that our proposed framework enhances the performance of
RAG systems equipped with different retrievers and is applicable to various
LLMs.
