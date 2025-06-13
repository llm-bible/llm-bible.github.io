---
layout: publication
title: 'Atomr: Atomic Operator-empowered Large Language Models For Heterogeneous Knowledge Reasoning'
authors: Amy Xin, Jinxin Liu, Zijun Yao, Zhicheng Lee, Shulin Cao, Lei Hou, Juanzi Li
conference: "Arxiv"
year: 2024
bibkey: xin2024atomic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.16495"}
tags: ['RAG', 'Applications', 'Tools']
---
Despite the outstanding capabilities of large language models (LLMs),
knowledge-intensive reasoning still remains a challenging task due to LLMs'
limitations in compositional reasoning and the hallucination problem. A
prevalent solution is to employ chain-of-thought (CoT) with retrieval-augmented
generation (RAG), which first formulates a reasoning plan by decomposing
complex questions into simpler sub-questions, and then applies iterative RAG at
each sub-question. However, prior works exhibit two crucial problems:
inadequate reasoning planning and poor incorporation of heterogeneous
knowledge. In this paper, we introduce AtomR, a framework for LLMs to conduct
accurate heterogeneous knowledge reasoning at the atomic level. Inspired by how
knowledge graph query languages model compositional reasoning through combining
predefined operations, we propose three atomic knowledge operators, a unified
set of operators for LLMs to retrieve and manipulate knowledge from
heterogeneous sources. First, in the reasoning planning stage, AtomR decomposes
a complex question into a reasoning tree where each leaf node corresponds to an
atomic knowledge operator, achieving question decomposition that is highly
fine-grained and orthogonal. Subsequently, in the reasoning execution stage,
AtomR executes each atomic knowledge operator, which flexibly selects,
retrieves, and operates atomic level knowledge from heterogeneous sources. We
also introduce BlendQA, a challenging benchmark specially tailored for
heterogeneous knowledge reasoning. Experiments on three single-source and two
multi-source datasets show that AtomR outperforms state-of-the-art baselines by
a large margin, with F1 score improvements of 9.4% on 2WikiMultihop and 9.5% on
BlendQA. We release our code and datasets.
