---
layout: publication
title: 'No-skim: Towards Efficiency Robustness Evaluation On Skimming-based Language Models'
authors: Shengyao Zhang, Mi Zhang, Xudong Pan, Min Yang
conference: "Arxiv"
year: 2023
bibkey: zhang2023no
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.09494'}
tags: ['RAG', 'Efficiency and Optimization', 'Security', 'Model Architecture', 'Tools', 'BERT']
---
To reduce the computation cost and the energy consumption in large language
models (LLM), skimming-based acceleration dynamically drops unimportant tokens
of the input sequence progressively along layers of the LLM while preserving
the tokens of semantic importance. However, our work for the first time reveals
the acceleration may be vulnerable to Denial-of-Service (DoS) attacks. In this
paper, we propose No-Skim, a general framework to help the owners of
skimming-based LLM to understand and measure the robustness of their
acceleration scheme. Specifically, our framework searches minimal and
unnoticeable perturbations at character-level and token-level to generate
adversarial inputs that sufficiently increase the remaining token ratio, thus
increasing the computation cost and energy consumption. We systematically
evaluate the vulnerability of the skimming acceleration in various LLM
architectures including BERT and RoBERTa on the GLUE benchmark. In the worst
case, the perturbation found by No-Skim substantially increases the running
cost of LLM by over 145% on average. Moreover, No-Skim extends the evaluation
framework to various scenarios, making the evaluation conductible with
different level of knowledge.
