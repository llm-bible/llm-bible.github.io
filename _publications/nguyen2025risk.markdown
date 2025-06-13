---
layout: publication
title: 'Risk-aware Distributional Intervention Policies For Language Models'
authors: Bao Nguyen, Binh Nguyen, Duy Nguyen, Viet Anh Nguyen
conference: "Arxiv"
year: 2025
bibkey: nguyen2025risk
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15758"}
tags: ['Attention Mechanism', 'Model Architecture']
---
Language models are prone to occasionally undesirable generations, such as
harmful or toxic content, despite their impressive capability to produce texts
that appear accurate and coherent. This paper presents a new two-stage approach
to detect and mitigate undesirable content generations by rectifying
activations. First, we train an ensemble of layerwise classifiers to detect
undesirable content using activations by minimizing a smooth surrogate of the
risk-aware score. Then, for contents that are detected as undesirable, we
propose layerwise distributional intervention policies that perturb the
attention heads minimally while guaranteeing probabilistically the
effectiveness of the intervention. Benchmarks on several language models and
datasets show that our method outperforms baselines in reducing the generation
of undesirable output.
