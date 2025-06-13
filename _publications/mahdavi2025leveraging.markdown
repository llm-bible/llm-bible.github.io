---
layout: publication
title: 'Leveraging Online Olympiad-level Math Problems For Llms Training And Contamination-resistant Evaluation'
authors: Sadegh Mahdavi, Muchen Li, Kaiwen Liu, Christos Thrampoulidis, Leonid Sigal, Renjie Liao
conference: "Arxiv"
year: 2025
bibkey: mahdavi2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.14275"}
  - {name: "Code", url: "https://github.com/DSL-Lab/aops"}
tags: ['Fine-Tuning', 'Pre-Training', 'RAG', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Advances in Large Language Models (LLMs) have sparked interest in their
ability to solve Olympiad-level math problems. However, the training and
evaluation of these models are constrained by the limited size and quality of
available datasets, as creating large-scale data for such advanced problems
requires extensive effort from human experts. In addition, current benchmarks
are prone to contamination, leading to unreliable evaluations. In this paper,
we present an automated pipeline that leverages the rich resources of the Art
of Problem Solving (AoPS) forum, which predominantly features Olympiad-level
problems and community-driven solutions. Using open-source LLMs, we develop a
method to extract question-answer pairs from the forum, resulting in
AoPS-Instruct, a dataset of more than 600,000 high-quality QA pairs. Our
experiments demonstrate that fine-tuning LLMs on AoPS-Instruct improves their
reasoning abilities across various benchmarks. Moreover, we build an automatic
pipeline that introduces LiveAoPSBench, an evolving evaluation set with
timestamps, derived from the latest forum data, providing a
contamination-resistant benchmark for assessing LLM performance. Notably, we
observe a significant decline in LLM performance over time, suggesting their
success on older examples may stem from pre-training exposure rather than true
reasoning ability. Our work presents a scalable approach to creating and
maintaining large-scale, high-quality datasets for advanced math reasoning,
offering valuable insights into the capabilities and limitations of LLMs in
this domain. Our benchmark and code is available at
https://github.com/DSL-Lab/aops
