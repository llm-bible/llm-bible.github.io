---
layout: publication
title: 'Quantifying And Mitigating Unimodal Biases In Multimodal Large Language Models: A Causal Perspective'
authors: Meiqi Chen, Yixin Cao, Yan Zhang, Chaochao Lu
conference: "Arxiv"
year: 2024
bibkey: chen2024quantifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.18346'}
  - {name: "Code", url: 'https://github.com/OpenCausaLab/MORE'}
tags: ['Agentic', 'Has Code', 'Tools', 'Applications', 'Multimodal Models', 'Bias Mitigation', 'Reinforcement Learning', 'Ethics and Bias']
---
Recent advancements in Large Language Models (LLMs) have facilitated the
development of Multimodal LLMs (MLLMs). Despite their impressive capabilities,
MLLMs often suffer from over-reliance on unimodal biases (e.g., language bias
and vision bias), leading to incorrect answers or hallucinations in complex
multimodal tasks. To investigate this issue, we propose a causal framework to
interpret the biases in Visual Question Answering (VQA) problems. Within this
framework, we conduct an in-depth causal analysis to assess the causal effect
of these biases on MLLM predictions. Based on the analysis, we introduce 1) a
novel MORE dataset with 12,000 challenging VQA instances requiring multi-hop
reasoning and overcoming unimodal biases. 2) a causality-enhanced agent
framework CAVE that guides models to comprehensively integrate information from
different modalities and mitigate biases. Our experiments show that MLLMs
perform poorly on MORE, indicating strong unimodal biases and limited semantic
understanding. However, when integrated with our CAVE, promising improvements
in reasoning and bias mitigation can be seen. These findings provide important
insights for the development of more robust MLLMs and contribute to the broader
goal of advancing multimodal AI systems capable of deeper understanding and
reasoning. Our project page is at https://github.com/OpenCausaLab/MORE.
