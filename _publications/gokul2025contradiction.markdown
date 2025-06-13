---
layout: publication
title: 'Contradiction Detection In RAG Systems: Evaluating Llms As Context Validators For Improved Information Consistency'
authors: Vignesh Gokul, Srikanth Tenneti, Alwarappan Nakkiran
conference: "Arxiv"
year: 2025
bibkey: gokul2025contradiction
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00180'}
tags: ['RAG', 'Security', 'Model Architecture', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Retrieval Augmented Generation (RAG) systems have emerged as a powerful
method for enhancing large language models (LLMs) with up-to-date information.
However, the retrieval step in RAG can sometimes surface documents containing
contradictory information, particularly in rapidly evolving domains such as
news. These contradictions can significantly impact the performance of LLMs,
leading to inconsistent or erroneous outputs. This study addresses this
critical challenge in two ways. First, we present a novel data generation
framework to simulate different types of contradictions that may occur in the
retrieval stage of a RAG system. Second, we evaluate the robustness of
different LLMs in performing as context validators, assessing their ability to
detect contradictory information within retrieved document sets. Our
experimental results reveal that context validation remains a challenging task
even for state-of-the-art LLMs, with performance varying significantly across
different types of contradictions. While larger models generally perform better
at contradiction detection, the effectiveness of different prompting strategies
varies across tasks and model architectures. We find that chain-of-thought
prompting shows notable improvements for some models but may hinder performance
in others, highlighting the complexity of the task and the need for more robust
approaches to context validation in RAG systems.
