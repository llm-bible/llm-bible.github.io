---
layout: publication
title: 'Pandora: A Code-driven Large Language Model Agent For Unified Reasoning Across Diverse Structured Knowledge'
authors: Yongrui Chen, Junhao He, Linbo Fu, Shenyu Zhang, Rihui Jin, Xinbang Dai, Jiaqi Li, Dehai Min, Nan Hu, Yuxin Zhang, Guilin Qi, Yi Huang, Tongtong Wu
conference: "Arxiv"
year: 2025
bibkey: chen2025code
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12734'}
tags: ['Agentic', 'RAG', 'Training Techniques', 'Applications', 'Tools', 'Pre-Training']
---
Unified Structured Knowledge Reasoning (USKR) aims to answer natural language
questions (NLQs) by using structured sources such as tables, databases, and
knowledge graphs in a unified way. Existing USKR methods either rely on
employing task-specific strategies or custom-defined representations, which
struggle to leverage the knowledge transfer between different SKR tasks or
align with the prior of LLMs, thereby limiting their performance. This paper
proposes a novel USKR framework named \textsc\{Pandora\}, which takes advantage
of \textsc\{Python\}'s \textsc\{Pandas\} API to construct a unified knowledge
representation for alignment with LLM pre-training. It employs an LLM to
generate textual reasoning steps and executable Python code for each question.
Demonstrations are drawn from a memory of training examples that cover various
SKR tasks, facilitating knowledge transfer. Extensive experiments on four
benchmarks involving three SKR tasks demonstrate that \textsc\{Pandora\}
outperforms existing unified frameworks and competes effectively with
task-specific methods.
