---
layout: publication
title: 'ICLERB: In-context Learning Embedding And Reranker Benchmark'
authors: Marie Al Ghossein, Emile Contal, Alexandre Robicquet
conference: "Arxiv"
year: 2024
bibkey: ghossein2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18947"}
tags: ['Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
In-Context Learning (ICL) enables Large Language Models (LLMs) to perform new
tasks by conditioning on prompts with relevant information. Retrieval-Augmented
Generation (RAG) enhances ICL by incorporating retrieved documents into the
LLM's context at query time. However, traditional retrieval methods focus on
semantic relevance, treating retrieval as a search problem. In this paper, we
propose reframing retrieval for ICL as a recommendation problem, aiming to
select documents that maximize utility in ICL tasks. We introduce the
In-Context Learning Embedding and Reranker Benchmark (ICLERB), a novel
evaluation framework that compares retrievers based on their ability to enhance
LLM accuracy in ICL settings. Additionally, we propose a novel Reinforcement
Learning-to-Rank from AI Feedback (RLRAIF) algorithm, designed to fine-tune
retrieval models using minimal feedback from the LLM. Our experimental results
reveal notable differences between ICLERB and existing benchmarks, and
demonstrate that small models fine-tuned with our RLRAIF algorithm outperform
large state-of-the-art retrieval models. These findings highlight the
limitations of existing evaluation methods and the need for specialized
benchmarks and training strategies adapted to ICL.
