---
layout: publication
title: 'Exlm: Rethinking The Impact Of [MASK] Tokens In Masked Language Models'
authors: Kangjie Zheng, Junwei Yang, Siyue Liang, Bin Feng, Zequn Liu, Wei Ju, Zhiping Xiao, Ming Zhang
conference: "Arxiv"
year: 2025
bibkey: zheng2025rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13397"}
tags: ['Masked Language Model', 'Multimodal Models', 'Training Techniques', 'Pretraining Methods', 'BERT', 'Pre-Training']
---
Masked Language Models (MLMs) have achieved remarkable success in many
self-supervised representation learning tasks. MLMs are trained by randomly
masking portions of the input sequences with [MASK] tokens and learning to
reconstruct the original content based on the remaining context. This paper
explores the impact of [MASK] tokens on MLMs. Analytical studies show that
masking tokens can introduce the corrupted semantics problem, wherein the
corrupted context may convey multiple, ambiguous meanings. This problem is also
a key factor affecting the performance of MLMs on downstream tasks. Based on
these findings, we propose a novel enhanced-context MLM, ExLM. Our approach
expands [MASK] tokens in the input context and models the dependencies between
these expanded states. This enhancement increases context capacity and enables
the model to capture richer semantic information, effectively mitigating the
corrupted semantics problem during pre-training. Experimental results
demonstrate that ExLM achieves significant performance improvements in both
text modeling and SMILES modeling tasks. Further analysis confirms that ExLM
enriches semantic representations through context enhancement, and effectively
reduces the semantic multimodality commonly observed in MLMs.
