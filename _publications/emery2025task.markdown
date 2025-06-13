---
layout: publication
title: 'Hallumix: A Task-agnostic, Multi-domain Benchmark For Real-world Hallucination Detection'
authors: Deanna Emery, Michael Goitia, Freddie Vargus, Iulia Neagu
conference: "Arxiv"
year: 2025
bibkey: emery2025task
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00506'}
tags: ['Reinforcement Learning', 'RAG', 'Applications']
---
As large language models (LLMs) are increasingly deployed in high-stakes
domains, detecting hallucinated content\\(\unicode\{x2013\}\\)text that is not
grounded in supporting evidence\\(\unicode\{x2013\}\\)has become a critical
challenge. Existing benchmarks for hallucination detection are often
synthetically generated, narrowly focused on extractive question answering, and
fail to capture the complexity of real-world scenarios involving multi-document
contexts and full-sentence outputs. We introduce the HalluMix Benchmark, a
diverse, task-agnostic dataset that includes examples from a range of domains
and formats. Using this benchmark, we evaluate seven hallucination detection
systems\\(\unicode\{x2013\}\\)both open and closed
source\\(\unicode\{x2013\}\\)highlighting differences in performance across tasks,
document lengths, and input representations. Our analysis highlights
substantial performance disparities between short and long contexts, with
critical implications for real-world Retrieval Augmented Generation (RAG)
implementations. Quotient Detections achieves the best overall performance,
with an accuracy of 0.82 and an F1 score of 0.84.
