---
layout: publication
title: 'Language Model Preference Evaluation With Multiple Weak Evaluators'
authors: Zhengyu Hu, Jieyu Zhang, Zhihan Xiong, Alexander Ratner, Hui Xiong, Ranjay Krishna
conference: "Arxiv"
year: 2024
bibkey: hu2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12869"}
tags: ['RAG', 'Tools', 'Applications']
---
Despite the remarkable success of Large Language Models (LLMs), evaluating
their outputs' quality regarding *preference* remains a critical challenge.
Existing works usually leverage an LLM as the judge for comparing LLMs' output
pairwisely, yet such model-based evaluator is *weak evaluator* due to
*conflicting preference*, i.e., output A is better than B, B than C, but C than
A, causing contradictory evaluation results. To address this, we introduce GED
(Preference Graph Ensemble and Denoise), a novel approach that leverages
multiple model-based evaluators to construct preference graphs, and then
ensemble and denoise these graphs for better, non-contradictory evaluation
results. In particular, our method consists of two primary stages: aggregating
evaluations into a unified graph and applying a denoising process to eliminate
cyclic inconsistencies, ensuring a directed acyclic graph (DAG) structure. We
provide theoretical guarantees for our framework, demonstrating its efficacy in
recovering the ground truth preference structure. Extensive experiments on ten
benchmarks demonstrate GED's superiority in three applications: model ranking,
response selection, and model alignment tasks. Notably, GED combines small LLM
evaluators (e.g., Llama3-8B, Mistral-7B, Qwen2-7B) to outperform stronger ones
(e.g., Qwen2-72B), showcasing its effectiveness in enhancing evaluation
reliability and improving model performance.
