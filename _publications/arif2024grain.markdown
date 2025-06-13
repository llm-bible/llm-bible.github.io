---
layout: publication
title: 'With A Grain Of SALT: Are Llms Fair Across Social Dimensions?'
authors: Samee Arif, Zohaib Khan, Maaidah Kaleem, Suhaib Rashid, Agha Ali Raza, Awais Athar
conference: "Arxiv"
year: 2024
bibkey: arif2024grain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12499"}
tags: ['Bias Mitigation', 'Ethics and Bias', 'Applications', 'Reinforcement Learning']
---
This paper presents a systematic analysis of biases in open-source Large
Language Models (LLMs), across gender, religion, and race. Our study evaluates
bias in smaller-scale Llama and Gemma models using the SALT (\\(\textbf\{S\}\\)ocial
\\(\textbf\{A\}\\)ppropriateness in \\(\textbf\{L\}\\)LM-Generated \\(\textbf\{T\}\\)ext)
dataset, which incorporates five distinct bias triggers: General Debate,
Positioned Debate, Career Advice, Problem Solving, and CV Generation. To
quantify bias, we measure win rates in General Debate and the assignment of
negative roles in Positioned Debate. For real-world use cases, such as Career
Advice, Problem Solving, and CV Generation, we anonymize the outputs to remove
explicit demographic identifiers and use DeepSeek-R1 as an automated evaluator.
We also address inherent biases in LLM-based evaluation, including evaluation
bias, positional bias, and length bias, and validate our results through human
evaluations. Our findings reveal consistent polarization across models, with
certain demographic groups receiving systematically favorable or unfavorable
treatment. By introducing SALT, we provide a comprehensive benchmark for bias
analysis and underscore the need for robust bias mitigation strategies in the
development of equitable AI systems.
