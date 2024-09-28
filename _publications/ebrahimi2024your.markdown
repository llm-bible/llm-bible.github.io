---
layout: publication
title: Your Context Is Not an Array Unveiling Random Access Limitations in Transformers
authors: Ebrahimi Mohammadreza, Panchal Sunny, Memisevic Roland
conference: "Arxiv"
year: 2024
bibkey: ebrahimi2024your
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05506"}
tags: ['ARXIV', 'Attention Mechanism', 'Model Architecture', 'Reinforcement Learning', 'Transformer']
---
Despite their recent successes Transformer-based large language models show surprising failure modes. A well-known example of such failure modes is their inability to length-generalize solving problem instances at inference time that are longer than those seen during training. In this work we further explore the root cause of this failure by performing a detailed analysis of model behaviors on the simple parity task. Our analysis suggests that length generalization failures are intricately related to a models inability to perform random memory accesses within its context window. We present supporting evidence for this hypothesis by demonstrating the effectiveness of methodologies that circumvent the need for indexing or that enable random token access indirectly through content-based addressing. We further show where and how the failure to perform random memory access manifests through attention map visualizations.
