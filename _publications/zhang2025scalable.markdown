---
layout: publication
title: 'SCE: Scalable Consistency Ensembles Make Blackbox Large Language Model Generation More Reliable'
authors: Jiaxin Zhang, Zhuohang Li, Wendi Cui, Kamalika Das, Bradley Malin, Sricharan Kumar
conference: "Arxiv"
year: 2025
bibkey: zhang2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10881"}
tags: ['Tools', 'Prompting', 'Merging']
---
Large language models (LLMs) have demonstrated remarkable performance, yet
their diverse strengths and weaknesses prevent any single LLM from achieving
dominance across all tasks. Ensembling multiple LLMs is a promising approach to
generate reliable responses but conventional ensembling frameworks suffer from
high computational overheads. This work introduces Scalable Consistency
Ensemble (SCE), an efficient framework for ensembling LLMs by prompting
consistent outputs. The SCE framework systematically evaluates and integrates
outputs to produce a cohesive result through two core components: SCE-CHECK, a
mechanism that gauges the consistency between response pairs via semantic
equivalence; and SCE-FUSION, which adeptly merges the highest-ranked consistent
responses from SCE-CHECK, to optimize collective strengths and mitigating
potential weaknesses. To improve the scalability with multiple inference
queries, we further propose ``\{You Only Prompt Once\}'' (YOPO), a novel
technique that reduces the inference complexity of pairwise comparison from
quadratic to constant time. We perform extensive empirical evaluations on
diverse benchmark datasets to demonstrate \methodName's effectiveness. Notably,
the \saccheckcomponent outperforms conventional baselines with enhanced
performance and a significant reduction in computational overhead.
