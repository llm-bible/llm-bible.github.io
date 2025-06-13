---
layout: publication
title: 'Benchmarking Adversarial Robustness To Bias Elicitation In Large Language Models: Scalable Automated Assessment With Llm-as-a-judge'
authors: Riccardo Cantini, Alessio Orsino, Massimo Ruggiero, Domenico Talia
conference: "Arxiv"
year: 2025
bibkey: cantini2025benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07887"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Training Techniques', 'Fairness', 'Tools', 'Bias Mitigation', 'Ethics and Bias', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have revolutionized artificial intelligence,
driving advancements in machine translation, summarization, and conversational
agents. However, their increasing integration into critical societal domains
has raised concerns about embedded biases, which can perpetuate stereotypes and
compromise fairness. These biases stem from various sources, including
historical inequalities in training data, linguistic imbalances, and
adversarial manipulation. Despite mitigation efforts, recent studies indicate
that LLMs remain vulnerable to adversarial attacks designed to elicit biased
responses. This work proposes a scalable benchmarking framework to evaluate LLM
robustness against adversarial bias elicitation. Our methodology involves (i)
systematically probing models with a multi-task approach targeting biases
across various sociocultural dimensions, (ii) quantifying robustness through
safety scores using an LLM-as-a-Judge approach for automated assessment of
model responses, and (iii) employing jailbreak techniques to investigate
vulnerabilities in safety mechanisms. Our analysis examines prevalent biases in
both small and large state-of-the-art models and their impact on model safety.
Additionally, we assess the safety of domain-specific models fine-tuned for
critical fields, such as medicine. Finally, we release a curated dataset of
bias-related prompts, CLEAR-Bias, to facilitate systematic vulnerability
benchmarking. Our findings reveal critical trade-offs between model size and
safety, aiding the development of fairer and more robust future language
models.
