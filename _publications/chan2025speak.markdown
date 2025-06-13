---
layout: publication
title: 'Speak Easy: Eliciting Harmful Jailbreaks From Llms With Simple Interactions'
authors: Yik Siu Chan, Narutatsu Ri, Yuxin Xiao, Marzyeh Ghassemi
conference: "Arxiv"
year: 2025
bibkey: chan2025speak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04322"}
tags: ['Responsible AI', 'Security', 'Tools', 'Reinforcement Learning', 'RAG']
---
Despite extensive safety alignment efforts, large language models (LLMs)
remain vulnerable to jailbreak attacks that elicit harmful behavior. While
existing studies predominantly focus on attack methods that require technical
expertise, two critical questions remain underexplored: (1) Are jailbroken
responses truly useful in enabling average users to carry out harmful actions?
(2) Do safety vulnerabilities exist in more common, simple human-LLM
interactions? In this paper, we demonstrate that LLM responses most effectively
facilitate harmful actions when they are both actionable and informative--two
attributes easily elicited in multi-step, multilingual interactions. Using this
insight, we propose HarmScore, a jailbreak metric that measures how effectively
an LLM response enables harmful actions, and Speak Easy, a simple multi-step,
multilingual attack framework. Notably, by incorporating Speak Easy into direct
request and jailbreak baselines, we see an average absolute increase of 0.319
in Attack Success Rate and 0.426 in HarmScore in both open-source and
proprietary LLMs across four safety benchmarks. Our work reveals a critical yet
often overlooked vulnerability: Malicious users can easily exploit common
interaction patterns for harmful intentions.
