---
layout: publication
title: 'Code Copycat Conundrum: Demystifying Repetition In Llm-based Code Generation'
authors: Mingwei Liu, Juntao Li, Ying Wang, Xueying Du, Zuoyu Ou, Qiuyuan Chen, Bingxu An, Zhao Wei, Yong Xu, Fangming Zou, Xin Peng, Yiling Lou
conference: "Arxiv"
year: 2025
bibkey: liu2025code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12608"}
tags: ['RAG', 'Applications']
---
Despite recent advances in Large Language Models (LLMs) for code generation,
the quality of LLM-generated code still faces significant challenges. One
significant issue is code repetition, which refers to the model's tendency to
generate structurally redundant code, resulting in inefficiencies and reduced
readability. To address this, we conduct the first empirical study to
investigate the prevalence and nature of repetition across 19 state-of-the-art
code LLMs using three widely-used benchmarks. Our study includes both
quantitative and qualitative analyses, revealing that repetition is pervasive
and manifests at various granularities and extents, including character,
statement, and block levels. We further summarize a taxonomy of 20 repetition
patterns. Building on our findings, we propose DeRep, a rule-based technique
designed to detect and mitigate repetition in generated code. We evaluate DeRep
using both open-source benchmarks and in an industrial setting. Our results
demonstrate that DeRep significantly outperforms baselines in reducing
repetition (with an average improvements of 91.3%, 93.5%, and 79.9% in rep-3,
rep-line, and sim-line metrics) and enhancing code quality (with a Pass@1
increase of 208.3% over greedy search). Furthermore, integrating DeRep improves
the performance of existing repetition mitigation methods, with Pass@1
improvements ranging from 53.7% to 215.7%.
