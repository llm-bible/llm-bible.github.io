---
layout: publication
title: 'Fact, Fetch, And Reason: A Unified Evaluation Of Retrieval-augmented Generation'
authors: Satyapriya Krishna, Kalpesh Krishna, Anhad Mohananey, Steven Schwarcz, Adam Stambler, Shyam Upadhyay, Manaal Faruqui
conference: "Arxiv"
year: 2024
bibkey: krishna2024unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12941"}
tags: ['RAG', 'Tools', 'Merging', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated significant performance
improvements across various cognitive tasks. An emerging application is using
LLMs to enhance retrieval-augmented generation (RAG) capabilities. These
systems require LLMs to understand user queries, retrieve relevant information,
and synthesize coherent and accurate responses. Given the increasing real-world
deployment of such systems, comprehensive evaluation becomes crucial. To this
end, we propose FRAMES (Factuality, Retrieval, And reasoning MEasurement Set),
a high-quality evaluation dataset designed to test LLMs' ability to provide
factual responses, assess retrieval capabilities, and evaluate the reasoning
required to generate final answers. While previous work has provided datasets
and benchmarks to evaluate these abilities in isolation, FRAMES offers a
unified framework that provides a clearer picture of LLM performance in
end-to-end RAG scenarios. Our dataset comprises challenging multi-hop questions
that require the integration of information from multiple sources. We present
baseline results demonstrating that even state-of-the-art LLMs struggle with
this task, achieving 0.40 accuracy with no retrieval. The accuracy is
significantly improved with our proposed multi-step retrieval pipeline,
achieving an accuracy of 0.66 (>50% improvement). We hope our work will help
bridge evaluation gaps and assist in developing more robust and capable RAG
systems.
