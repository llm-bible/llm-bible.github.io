---
layout: publication
title: 'Bridging The Safety Gap: A Guardrail Pipeline For Trustworthy LLM Inferences'
authors: Shanshan Han, Salman Avestimehr, Chaoyang He
conference: "Arxiv"
year: 2025
bibkey: han2025bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08142"}
tags: ['Responsible AI', 'Interpretability and Explainability', 'Tools', 'Reinforcement Learning']
---
We present Wildflare GuardRail, a guardrail pipeline designed to enhance the
safety and reliability of Large Language Model (LLM) inferences by
systematically addressing risks across the entire processing workflow.
Wildflare GuardRail integrates several core functional modules, including
Safety Detector that identifies unsafe inputs and detects hallucinations in
model outputs while generating root-cause explanations, Grounding that
contextualizes user queries with information retrieved from vector databases,
Customizer that adjusts outputs in real time using lightweight, rule-based
wrappers, and Repairer that corrects erroneous LLM outputs using hallucination
explanations provided by Safety Detector. Results show that our unsafe content
detection model in Safety Detector achieves comparable performance with OpenAI
API, though trained on a small dataset constructed with several public
datasets. Meanwhile, the lightweight wrappers can address malicious URLs in
model outputs in 1.06s per query with 100% accuracy without costly model calls.
Moreover, the hallucination fixing model demonstrates effectiveness in reducing
hallucinations with an accuracy of 80.7%.
