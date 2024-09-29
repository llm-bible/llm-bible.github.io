---
layout: publication
title: Impact Of Non45;standard Unicode Characters On Security And Comprehension In Large Language Models
authors: Daniel Johan S, Pal Anand
conference: "Arxiv"
year: 2024
bibkey: daniel2024impact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14490"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
The advancement of large language models has significantly improved natural language processing. However challenges such as jailbreaks (prompt injections that cause an LLM to follow instructions contrary to its intended use) hallucinations (generating incorrect or misleading information) and comprehension errors remain prevalent. In this report we present a comparative analysis of the performance of fifteen distinct models with each model undergoing a standardized test comprising 38 queries across three key metrics jailbreaks hallucinations and comprehension errors. The models are assessed based on the total occurrences of jailbreaks hallucinations and comprehension errors. Our work exposes these models inherent vulnerabilities and challenges the notion of human45;level language comprehension of these models. We have empirically analysed the impact of non45;standard Unicode characters on LLMs and their safeguarding mechanisms on the best45;performing LLMs including GPT45;4 Gemini 1.5 Pro LlaMA45;345;70B and Claude 3 Opus. By incorporating alphanumeric symbols from Unicode outside the standard Latin block and variants of characters in other languages we observed a reduction in the efficacy of guardrails implemented through Reinforcement Learning Human Feedback (RLHF). Consequently these models exhibit heightened vulnerability to content policy breaches and prompt leakage. Our study also suggests a need to incorporate non45;standard Unicode text in LLM training data to enhance the capabilities of these models.
