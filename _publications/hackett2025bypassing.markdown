---
layout: publication
title: 'Bypassing Prompt Injection And Jailbreak Detection In LLM Guardrails'
authors: William Hackett, Lewis Birch, Stefan Trawicki, Neeraj Suri, Peter Garraghan
conference: "Arxiv"
year: 2025
bibkey: hackett2025bypassing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.11168'}
tags: ['RAG', 'Prompting', 'Security']
---
Large Language Models (LLMs) guardrail systems are designed to protect
against prompt injection and jailbreak attacks. However, they remain vulnerable
to evasion techniques. We demonstrate two approaches for bypassing LLM prompt
injection and jailbreak detection systems via traditional character injection
methods and algorithmic Adversarial Machine Learning (AML) evasion techniques.
Through testing against six prominent protection systems, including Microsoft's
Azure Prompt Shield and Meta's Prompt Guard, we show that both methods can be
used to evade detection while maintaining adversarial utility achieving in some
instances up to 100% evasion success. Furthermore, we demonstrate that
adversaries can enhance Attack Success Rates (ASR) against black-box targets by
leveraging word importance ranking computed by offline white-box models. Our
findings reveal vulnerabilities within current LLM protection mechanisms and
highlight the need for more robust guardrail systems.
