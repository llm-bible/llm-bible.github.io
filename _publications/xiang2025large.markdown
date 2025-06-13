---
layout: publication
title: 'Modigen: A Large Language Model-based Workflow For Multi-task Modelica Code Generation'
authors: Jiahui Xiang, Tong Ye, Peiyu Liu, Yinan Zhang, Wenhai Wang
conference: "Arxiv"
year: 2025
bibkey: xiang2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18460"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Modelica is a widely adopted language for simulating complex physical
systems, yet effective model creation and optimization require substantial
domain expertise. Although large language models (LLMs) have demonstrated
promising capabilities in code generation, their application to modeling
remains largely unexplored. To address this gap, we have developed benchmark
datasets specifically designed to evaluate the performance of LLMs in
generating Modelica component models and test cases. Our evaluation reveals
substantial limitations in current LLMs, as the generated code often fails to
simulate successfully. To overcome these challenges, we propose a specialized
workflow that integrates supervised fine-tuning, graph retrieval-augmented
generation, and feedback optimization to improve the accuracy and reliability
of Modelica code generation. The evaluation results demonstrate significant
performance gains: the maximum improvement in pass@1 reached 0.3349 for the
component generation task and 0.2457 for the test case generation task. This
research underscores the potential of LLMs to advance intelligent modeling
tools and offers valuable insights for future developments in system modeling
and engineering applications.
