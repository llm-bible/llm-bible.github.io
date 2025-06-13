---
layout: publication
title: 'Perceive, Query & Reason: Enhancing Video QA With Question-guided Temporal Queries'
authors: Roberto Amoroso, Gengyuan Zhang, Rajat Koner, Lorenzo Baraldi, Rita Cucchiara, Volker Tresp
conference: "Arxiv"
year: 2024
bibkey: amoroso2024query
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.19304'}
tags: ['RAG', 'Multimodal Models', 'Applications']
---
Video Question Answering (Video QA) is a challenging video understanding task
that requires models to comprehend entire videos, identify the most relevant
information based on contextual cues from a given question, and reason
accurately to provide answers. Recent advancements in Multimodal Large Language
Models (MLLMs) have transformed video QA by leveraging their exceptional
commonsense reasoning capabilities. This progress is largely driven by the
effective alignment between visual data and the language space of MLLMs.
However, for video QA, an additional space-time alignment poses a considerable
challenge for extracting question-relevant information across frames. In this
work, we investigate diverse temporal modeling techniques to integrate with
MLLMs, aiming to achieve question-guided temporal modeling that leverages
pre-trained visual and textual alignment in MLLMs. We propose T-Former, a novel
temporal modeling method that creates a question-guided temporal bridge between
frame-wise visual perception and the reasoning capabilities of LLMs. Our
evaluation across multiple video QA benchmarks demonstrates that T-Former
competes favorably with existing temporal modeling approaches and aligns with
recent advancements in video QA.
