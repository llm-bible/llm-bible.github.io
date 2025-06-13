---
layout: publication
title: 'Towards LLM Guardrails Via Sparse Representation Steering'
authors: Zeqing He, Zhibo Wang, Huiyu Xu, Kui Ren
conference: "Arxiv"
year: 2025
bibkey: he2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.16851'}
tags: ['Interpretability and Explainability', 'RAG', 'Fairness', 'Tools', 'Bias Mitigation', 'Ethics and Bias', 'Responsible AI']
---
Large Language Models (LLMs) have demonstrated remarkable performance in
natural language generation tasks, yet their uncontrolled outputs pose
significant ethical and safety risks. Recently, representation engineering
methods have shown promising results in steering model behavior by modifying
the rich semantic information encoded in activation vectors. However, due to
the difficulty of precisely disentangling semantic directions within
high-dimensional representation space, existing approaches suffer from three
major limitations: lack of fine-grained control, quality degradation of
generated content, and poor interpretability. To address these challenges, we
propose a sparse encoding-based representation engineering method, named SRE,
which decomposes polysemantic activations into a structured, monosemantic
feature space. By leveraging sparse autoencoding, our approach isolates and
adjusts only task-specific sparse feature dimensions, enabling precise and
interpretable steering of model behavior while preserving content quality. We
validate our method on three critical domains, i.e., safety, fairness, and
truthfulness using the open-source LLM Gemma-2-2B-it. Experimental results show
that SRE achieves superior controllability while maintaining the overall
quality of generated content (i.e., controllability and quality), demonstrating
its effectiveness as a fine-grained and interpretable activation steering
framework.
