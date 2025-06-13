---
layout: publication
title: 'Logictree: Structured Proof Exploration For Coherent And Rigorous Logical Reasoning With Large Language Models'
authors: Kang He, Kaushik Roy
conference: "Arxiv"
year: 2025
bibkey: he2025structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14089"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'RAG', 'Model Architecture']
---
Large language models (LLMs) have achieved remarkable multi-step reasoning
capabilities across various domains. However, LLMs still face distinct
challenges in complex logical reasoning, as (1) proof-finding requires
systematic exploration and the maintenance of logical coherence and (2)
searching the right combination of premises at each reasoning step is
inherently challenging in tasks with large premise space. To address this, we
propose LogicTree, an inference-time modular framework employing
algorithm-guided search to automate structured proof exploration and ensure
logical coherence. Advancing beyond tree-of-thought (ToT), we incorporate
caching mechanism into LogicTree to enable effective utilization of historical
knowledge, preventing reasoning stagnation and minimizing redundancy.
Furthermore, we address the combinatorial complexity of premise search by
decomposing it into a linear process. The refined premise selection restricts
subsequent inference to at most one derivation per step, enhancing reasoning
granularity and enforcing strict step-by-step reasoning. Additionally, we
introduce two LLM-free heuristics for premise prioritization, enabling
strategic proof search. Experimental results on five datasets demonstrate that
LogicTree optimally scales inference-time computation to achieve higher proof
accuracy, surpassing chain-of-thought (CoT) and ToT with average gains of 23.6%
and 12.5%, respectively, on GPT-4o. Moreover, within LogicTree, GPT-4o
outperforms o3-mini by 7.6% on average.
