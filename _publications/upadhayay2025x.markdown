---
layout: publication
title: 'X-guard: Multilingual Guard Agent For Content Moderation'
authors: Bibek Upadhayay, Vahid Behzadan, Ph. D
conference: "Arxiv"
year: 2025
bibkey: upadhayay2025x
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08848'}
tags: ['Agentic', 'Security', 'Model Architecture', 'Applications', 'Tools', 'Training Techniques', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'Responsible AI']
---
Large Language Models (LLMs) have rapidly become integral to numerous
applications in critical domains where reliability is paramount. Despite
significant advances in safety frameworks and guardrails, current protective
measures exhibit crucial vulnerabilities, particularly in multilingual
contexts. Existing safety systems remain susceptible to adversarial attacks in
low-resource languages and through code-switching techniques, primarily due to
their English-centric design. Furthermore, the development of effective
multilingual guardrails is constrained by the scarcity of diverse cross-lingual
training data. Even recent solutions like Llama Guard-3, while offering
multilingual support, lack transparency in their decision-making processes. We
address these challenges by introducing X-Guard agent, a transparent
multilingual safety agent designed to provide content moderation across diverse
linguistic contexts. X-Guard effectively defends against both conventional
low-resource language attacks and sophisticated code-switching attacks. Our
approach includes: curating and enhancing multiple open-source safety datasets
with explicit evaluation rationales; employing a jury of judges methodology to
mitigate individual judge LLM provider biases; creating a comprehensive
multilingual safety dataset spanning 132 languages with 5 million data points;
and developing a two-stage architecture combining a custom-finetuned mBART-50
translation module with an evaluation X-Guard 3B model trained through
supervised finetuning and GRPO training. Our empirical evaluations demonstrate
X-Guard's effectiveness in detecting unsafe content across multiple languages
while maintaining transparency throughout the safety evaluation process. Our
work represents a significant advancement in creating robust, transparent, and
linguistically inclusive safety systems for LLMs and its integrated systems.
