---
layout: publication
title: 'Knowing When To Ask -- Bridging Large Language Models And Data'
authors: Prashanth Radhakrishnan, Jennifer Chen, Bo Xu, Prem Ramaswami, Hannah Pho, Adriana Olmos, James Manyika, R. V. Guha
conference: "Arxiv"
year: 2024
bibkey: radhakrishnan2024knowing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13741"}
tags: ['RAG', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) are prone to generating factually incorrect
information when responding to queries that involve numerical and statistical
data or other timely facts. In this paper, we present an approach for enhancing
the accuracy of LLMs by integrating them with Data Commons, a vast, open-source
repository of public statistics from trusted organizations like the United
Nations (UN), Center for Disease Control and Prevention (CDC) and global census
bureaus. We explore two primary methods: Retrieval Interleaved Generation
(RIG), where the LLM is trained to produce natural language queries to retrieve
data from Data Commons, and Retrieval Augmented Generation (RAG), where
relevant data tables are fetched from Data Commons and used to augment the
LLM's prompt. We evaluate these methods on a diverse set of queries,
demonstrating their effectiveness in improving the factual accuracy of LLM
outputs. Our work represents an early step towards building more trustworthy
and reliable LLMs that are grounded in verifiable statistical data and capable
of complex factual reasoning.
