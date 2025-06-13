---
layout: publication
title: 'Propaganda Via AI? A Study On Semantic Backdoors In Large Language Models'
authors: Nay Myat Min, Long H. Pham, Yige Li, Jun Sun
conference: "Arxiv"
year: 2025
bibkey: min2025propaganda
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12344"}
  - {name: "Code", url: "https://github.com/NayMyatMin/RAVEN"}
tags: ['Tools', 'GPT', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Has Code', 'Prompting']
---
Large language models (LLMs) demonstrate remarkable performance across myriad
language tasks, yet they remain vulnerable to backdoor attacks, where
adversaries implant hidden triggers that systematically manipulate model
outputs. Traditional defenses focus on explicit token-level anomalies and
therefore overlook semantic backdoors-covert triggers embedded at the
conceptual level (e.g., ideological stances or cultural references) that rely
on meaning-based cues rather than lexical oddities. We first show, in a
controlled finetuning setting, that such semantic backdoors can be implanted
with only a small poisoned corpus, establishing their practical feasibility. We
then formalize the notion of semantic backdoors in LLMs and introduce a
black-box detection framework, RAVEN (short for "Response Anomaly Vigilance for
uncovering semantic backdoors"), which combines semantic entropy with
cross-model consistency analysis. The framework probes multiple models with
structured topic-perspective prompts, clusters the sampled responses via
bidirectional entailment, and flags anomalously uniform outputs; cross-model
comparison isolates model-specific anomalies from corpus-wide biases. Empirical
evaluations across diverse LLM families (GPT-4o, Llama, DeepSeek, Mistral)
uncover previously undetected semantic backdoors, providing the first
proof-of-concept evidence of these hidden vulnerabilities and underscoring the
urgent need for concept-level auditing of deployed language models. We
open-source our code and data at https://github.com/NayMyatMin/RAVEN.
