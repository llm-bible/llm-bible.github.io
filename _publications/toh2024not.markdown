---
layout: publication
title: 'Not All Votes Count! Programs As Verifiers Improve Self-consistency Of Language Models For Math Reasoning'
authors: Vernon Y. H. Toh, Deepanway Ghosal, Soujanya Poria
conference: "Arxiv"
year: 2024
bibkey: toh2024not
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.12608'}
  - {name: "Code", url: 'https://github.com/declare-lab/prove'}
tags: ['RAG', 'Has Code', 'Tools']
---
Large language models (LLMs) have shown increasing competence in solving
mathematical reasoning problems. However, many open-source LLMs still struggle
with errors in calculation and semantic understanding during intermediate
reasoning steps. In this work, we introduce Prove, a simple yet effective
framework that leverages translated programs derived from natural language
solutions as a verification mechanism to filter out potentially incorrect
reasoning paths before aggregating final answers. Unlike vanilla majority
voting, our approach filters out solutions whose corresponding program output
is inconsistent with the generated solution, aggregating only those that pass
verification. We conducted extensive experiments using 13 open-source LLMs from
various model families and sizes, ranging from 0.5B to 13B parameters, across
eight mathematical benchmarks. Our results show that Prove consistently
outperforms vanilla majority voting as a heuristic for solving mathematical
reasoning tasks across all model sizes and datasets, achieving improvements of
up to 18% on GSM8K and 8% on MATH-500. Our codes are available at
https://github.com/declare-lab/prove.
