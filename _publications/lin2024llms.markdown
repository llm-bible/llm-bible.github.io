---
layout: publication
title: 'Llms As Continuous Learners: Improving The Reproduction Of Defective Code In Software Issues'
authors: Yalan Lin, Yingwei Ma, Rongyu Cao, Binhua Li, Fei Huang, Xiaodong Gu, Yongbin Li
conference: "Arxiv"
year: 2024
bibkey: lin2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.13941"}
tags: ['Agentic', 'Merging', 'Tools', 'Reinforcement Learning']
---
Reproducing buggy code is the first and crucially important step in issue
resolving, as it aids in identifying the underlying problems and validating
that generated patches resolve the problem. While numerous approaches have been
proposed for this task, they primarily address common, widespread errors and
struggle to adapt to unique, evolving errors specific to individual code
repositories. To fill this gap, we propose EvoCoder, a multi-agent continuous
learning framework for issue code reproduction. EvoCoder adopts a reflection
mechanism that allows the LLM to continuously learn from previously resolved
problems and dynamically refine its strategies to new emerging challenges. To
prevent experience bloating, EvoCoder introduces a novel hierarchical
experience pool that enables the model to adaptively update common and
repo-specific experiences. Our experimental results show a 20% improvement in
issue reproduction rates over existing SOTA methods. Furthermore, integrating
our reproduction mechanism significantly boosts the overall accuracy of the
existing issue-resolving pipeline.
