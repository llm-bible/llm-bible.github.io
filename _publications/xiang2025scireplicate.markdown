---
layout: publication
title: 'Scireplicate-bench: Benchmarking Llms In Agent-driven Algorithmic Reproduction From Research Papers'
authors: Yanzheng Xiang, Hanqi Yan, Shuyin Ouyang, Lin Gui, Yulan He
conference: "Arxiv"
year: 2025
bibkey: xiang2025scireplicate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00255'}
  - {name: "Code", url: 'https://github.com/xyzCS/SciReplicate-Bench'}
tags: ['Agentic', 'Has Code', 'Tools']
---
This study evaluates large language models (LLMs) in generating code from
algorithm descriptions from recent NLP papers. The task requires two key
competencies: (1) algorithm comprehension: synthesizing information from papers
and academic literature to understand implementation logic, and (2) coding
expertise: identifying dependencies and correctly implementing necessary APIs.
To facilitate rigorous evaluation, we introduce SciReplicate-Bench, a benchmark
of 100 tasks from 36 NLP papers published in 2024, featuring detailed
annotations and comprehensive test cases. Building on SciReplicate-Bench, we
propose Sci-Reproducer, a multi-agent framework consisting of a Paper Agent
that interprets algorithmic concepts from literature and a Code Agent that
retrieves dependencies from repositories and implement solutions. To assess
algorithm understanding, we introduce reasoning graph accuracy, which
quantifies similarity between generated and reference reasoning graphs derived
from code comments and structure. For evaluating implementation quality, we
employ execution accuracy, CodeBLEU, and repository dependency/API recall
metrics. In our experiments, we evaluate various powerful Non-Reasoning LLMs
and Reasoning LLMs as foundational models. The best-performing LLM using
Sci-Reproducer achieves only 39% execution accuracy, highlighting the
benchmark's difficulty.Our analysis identifies missing or inconsistent
algorithm descriptions as key barriers to successful reproduction. We will
open-source our benchmark, and code at
https://github.com/xyzCS/SciReplicate-Bench.
