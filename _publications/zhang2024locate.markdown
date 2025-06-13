---
layout: publication
title: 'Locate-then-edit For Multi-hop Factual Recall Under Knowledge Editing'
authors: Zhuoran Zhang, Yongxiang Li, Zijian Kan, Keyuan Cheng, Lijie Hu, Di Wang
conference: "Arxiv"
year: 2024
bibkey: zhang2024locate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06331"}
tags: ['Interpretability and Explainability', 'RAG', 'Tools', 'Prompting']
---
The locate-then-edit paradigm has shown significant promise for knowledge
editing (KE) in Large Language Models (LLMs). While previous methods perform
well on single-hop fact recall tasks, they consistently struggle with multi-hop
factual recall tasks involving newly edited knowledge. In this paper,
leveraging tools in mechanistic interpretability, we first identify that in
multi-hop tasks, LLMs tend to retrieve knowledge with implicit subject
information from deeper MLP layers, unlike single-hop tasks, which rely on
shallow layers. This distinction explains the poor performance of current
methods in multi-hop queries, as they primarily focus on editing shallow layers
with single-hop edit prompts, leaving deeper layers unchanged. To address this,
we propose IFMET, a novel locate-then-edit KE approach designed to edit both
shallow and deep MLP layers. Beyond single-hop editing prompts, IFMET further
incorporates multi-hop editing prompts to locate and modify knowledge across
different stages of reasoning. Experimental results demonstrate that IFMET
significantly improves performance on multi-hop factual recall tasks,
overcoming the limitations of previous locate-then-edit methods
