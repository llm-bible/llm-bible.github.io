---
layout: publication
title: 'Gracore: Benchmarking Graph Comprehension And Complex Reasoning In Large Language Models'
authors: Zike Yuan, Ming Liu, Hui Wang, Bing Qin
conference: "Arxiv"
year: 2024
bibkey: yuan2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02936"}
  - {name: "Code", url: "https://github.com/ZIKEYUAN/GraCoRe"}
tags: ['Uncategorized', 'Has Code']
---
Evaluating the graph comprehension and reasoning abilities of Large Language
Models (LLMs) is challenging and often incomplete. Existing benchmarks focus
primarily on pure graph understanding, lacking a comprehensive evaluation
across all graph types and detailed capability definitions. This paper presents
GraCoRe, a benchmark for systematically assessing LLMs' graph comprehension and
reasoning. GraCoRe uses a three-tier hierarchical taxonomy to categorize and
test models on pure graph and heterogeneous graphs, subdividing capabilities
into 10 distinct areas tested through 19 tasks. Our benchmark includes 11
datasets with 5,140 graphs of varying complexity. We evaluate four
closed-source and eight open-source LLMs, conducting thorough analyses from
both ability and task perspectives. Key findings reveal that OpenAI o1 model
has amazing comprehension and reasoning capabilities, semantic enrichment
enhances reasoning performance, node ordering impacts task success, and the
ability to process longer texts does not necessarily improve graph
comprehension or reasoning.GraCoRe is open-sourced at
https://github.com/ZIKEYUAN/GraCoRe
