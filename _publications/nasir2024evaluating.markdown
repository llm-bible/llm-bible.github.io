---
layout: publication
title: 'Gametraversalbenchmark: Evaluating Planning Abilities Of Large Language Models Through Traversing 2D Game Maps'
authors: Muhammad Umair Nasir, Steven James, Julian Togelius
conference: "Arxiv"
year: 2024
bibkey: nasir2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07765"}
  - {name: "Code", url: "https://github.com/umair-nasir14/Game-Traversal-Benchmark"}
tags: ['GPT', 'Has Code', 'Model Architecture']
---
Large language models (LLMs) have recently demonstrated great success in
generating and understanding natural language. While they have also shown
potential beyond the domain of natural language, it remains an open question as
to what extent and in which way these LLMs can plan. We investigate their
planning capabilities by proposing GameTraversalBenchmark (GTB), a benchmark
consisting of diverse 2D grid-based game maps. An LLM succeeds if it can
traverse through given objectives, with a minimum number of steps and a minimum
number of generation errors. We evaluate a number of LLMs on GTB and found that
GPT-4-Turbo achieved the highest score of 44.97% on GTB\_Score (GTBS), a
composite score that combines the three above criteria. Furthermore, we
preliminarily test large reasoning models, namely o1, which scores \\(67.84%\\) on
GTBS, indicating that the benchmark remains challenging for current models.
Code, data, and documentation are available at
https://github.com/umair-nasir14/Game-Traversal-Benchmark.
