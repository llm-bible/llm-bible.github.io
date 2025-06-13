---
layout: publication
title: 'Agentharm: A Benchmark For Measuring Harmfulness Of LLM Agents'
authors: Maksym Andriushchenko, Alexandra Souly, Mateusz Dziemian, Derek Duenas, Maxwell Lin, Justin Wang, Dan Hendrycks, Andy Zou, Zico Kolter, Matt Fredrikson, Eric Winsor, Jerome Wynne, Yarin Gal, Xander Davies
conference: "Arxiv"
year: 2024
bibkey: andriushchenko2024benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09024"}
tags: ['Responsible AI', 'Agentic', 'Tools', 'Security', 'Prompting']
---
The robustness of LLMs to jailbreak attacks, where users design prompts to
circumvent safety measures and misuse model capabilities, has been studied
primarily for LLMs acting as simple chatbots. Meanwhile, LLM agents -- which
use external tools and can execute multi-stage tasks -- may pose a greater risk
if misused, but their robustness remains underexplored. To facilitate research
on LLM agent misuse, we propose a new benchmark called AgentHarm. The benchmark
includes a diverse set of 110 explicitly malicious agent tasks (440 with
augmentations), covering 11 harm categories including fraud, cybercrime, and
harassment. In addition to measuring whether models refuse harmful agentic
requests, scoring well on AgentHarm requires jailbroken agents to maintain
their capabilities following an attack to complete a multi-step task. We
evaluate a range of leading LLMs, and find (1) leading LLMs are surprisingly
compliant with malicious agent requests without jailbreaking, (2) simple
universal jailbreak templates can be adapted to effectively jailbreak agents,
and (3) these jailbreaks enable coherent and malicious multi-step agent
behavior and retain model capabilities. To enable simple and reliable
evaluation of attacks and defenses for LLM-based agents, we publicly release
AgentHarm at https://huggingface.co/datasets/ai-safety-institute/AgentHarm.
