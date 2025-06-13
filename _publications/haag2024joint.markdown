---
layout: publication
title: 'Joint Embeddings For Graph Instruction Tuning'
authors: Aaron Haag, Vlad Argatu, Oliver Lohse
conference: "Arxiv"
year: 2024
bibkey: haag2024joint
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20684"}
tags: ['Multimodal Models', 'Reinforcement Learning']
---
Large Language Models (LLMs) have achieved impressive performance in text
understanding and have become an essential tool for building smart assistants.
Originally focusing on text, they have been enhanced with multimodal
capabilities in recent works that successfully built visual instruction
following assistants. As far as the graph modality goes, however, no such
assistants have yet been developed. Graph structures are complex in that they
represent relation between different features and are permutation invariant.
Moreover, representing them in purely textual form does not always lead to good
LLM performance even for finetuned models. As a result, there is a need to
develop a new method to integrate graphs in LLMs for general graph
understanding. This work explores the integration of the graph modality in LLM
for general graph instruction following tasks. It aims at producing a deep
learning model that enhances an underlying LLM with graph embeddings and trains
it to understand them and to produce, given an instruction, an answer grounded
in the graph representation. The approach performs significantly better than a
graph to text approach and remains consistent even for larger graphs.
