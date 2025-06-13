---
layout: publication
title: 'TPIA: Towards Target-specific Prompt Injection Attack Against Code-oriented Large Language Models'
authors: Yuchen Yang, Hongwei Yao, Bingrun Yang, Yiling He, Yiming Li, Tianwei Zhang, Zhan Qin
conference: "Arxiv"
year: 2024
bibkey: yang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.09164"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'RAG', 'Prompting', 'Applications']
---
Recently, code-oriented large language models (Code LLMs) have been widely
and successfully exploited to simplify and facilitate programming.
Unfortunately, a few pioneering works revealed that these Code LLMs are
vulnerable to backdoor and adversarial attacks. The former poisons the training
data or model parameters, hijacking the LLMs to generate malicious code
snippets when encountering the trigger. The latter crafts malicious adversarial
input codes to reduce the quality of the generated codes. In this paper, we
reveal that both attacks have some inherent limitations: backdoor attacks rely
on the adversary's capability of controlling the model training process, which
may not be practical; adversarial attacks struggle with fulfilling specific
malicious purposes. To alleviate these problems, this paper presents a novel
attack paradigm against Code LLMs, namely target-specific prompt injection
attack (TPIA). TPIA generates non-functional perturbations containing the
information of malicious instructions and inserts them into the victim's code
context by spreading them into potentially used dependencies (e.g., packages or
RAG's knowledge base). It induces the Code LLMs to generate attacker-specified
malicious code snippets at the target location. In general, we compress the
attacker-specified malicious objective into the perturbation by adversarial
optimization based on greedy token search. We collect 13 representative
malicious objectives to design 31 threat cases for three popular programming
languages. We show that our TPIA can successfully attack three representative
open-source Code LLMs (with an attack success rate of up to 97.9%) and two
mainstream commercial Code LLM-integrated applications (with an attack success
rate of over 90%) in all threat cases, using only a 12-token non-functional
perturbation.
