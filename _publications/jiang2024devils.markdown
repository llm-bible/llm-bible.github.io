---
layout: publication
title: 'Devils In Middle Layers Of Large Vision-language Models: Interpreting, Detecting And Mitigating Object Hallucinations Via Attention Lens'
authors: Zhangqi Jiang, Junkai Chen, Beier Zhu, Tingjin Luo, Yankun Shen, Xu Yang
conference: "Arxiv"
year: 2024
bibkey: jiang2024devils
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.16724'}
  - {name: "Code", url: 'https://github.com/ZhangqiJiang07/middle_layers_indicating_hallucinations'}
tags: ['Attention Mechanism', 'Has Code', 'Training Techniques', 'Model Architecture', 'Multimodal Models']
---
Hallucinations in Large Vision-Language Models (LVLMs) significantly
undermine their reliability, motivating researchers to explore the causes of
hallucination. However, most studies primarily focus on the language aspect
rather than the visual. In this paper, we address how LVLMs process visual
information and whether this process causes hallucination. Firstly, we use the
attention lens to identify the stages at which LVLMs handle visual data,
discovering that the middle layers are crucial. Moreover, we find that these
layers can be further divided into two stages: ''visual information
enrichment'' and ''semantic refinement'' which respectively propagate visual
data to object tokens and interpret it through text. By analyzing attention
patterns during the visual information enrichment stage, we find that real
tokens consistently receive higher attention weights than hallucinated ones,
serving as a strong indicator of hallucination. Further examination of
multi-head attention maps reveals that hallucination tokens often result from
heads interacting with inconsistent objects. Based on these insights, we
propose a simple inference-time method that adjusts visual attention by
integrating information across various heads. Extensive experiments demonstrate
that this approach effectively mitigates hallucinations in mainstream LVLMs
without additional training costs. Code is available at
https://github.com/ZhangqiJiang07/middle_layers_indicating_hallucinations.
