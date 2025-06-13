---
layout: publication
title: 'IMPROVE: Iterative Model Pipeline Refinement And Optimization Leveraging LLM Experts'
authors: Eric Xue, Ke Chen, Zeyi Huang, Yuyang Ji, Yong Jae Lee, Haohan Wang
conference: "Arxiv"
year: 2025
bibkey: xue2025iterative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18530"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'RAG']
---
Large language model (LLM) agents have emerged as a promising solution to automate the workflow of machine learning, but most existing methods share a common limitation: they attempt to optimize entire pipelines in a single step before evaluation, making it difficult to attribute improvements to specific changes. This lack of granularity leads to unstable optimization and slower convergence, limiting their effectiveness. To address this, we introduce Iterative Refinement, a novel strategy for LLM-driven ML pipeline design inspired by how human ML experts iteratively refine models, focusing on one component at a time rather than making sweeping changes all at once. By systematically updating individual components based on real training feedback, Iterative Refinement improves overall model performance. We also provide some theoretical edvience of the superior properties of this Iterative Refinement. Further, we implement this strategy in IMPROVE, an end-to-end LLM agent framework for automating and optimizing object classification pipelines. Through extensive evaluations across datasets of varying sizes and domains, we demonstrate that Iterative Refinement enables IMPROVE to consistently achieve better performance over existing zero-shot LLM-based approaches.
