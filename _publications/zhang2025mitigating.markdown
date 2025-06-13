---
layout: publication
title: 'Mitigating Manipulation And Enhancing Persuasion: A Reflective Multi-agent Approach For Legal Argument Generation'
authors: Li Zhang, Kevin D. Ashley
conference: "Arxiv"
year: 2025
bibkey: zhang2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02992"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting']
---
Large Language Models (LLMs) are increasingly explored for legal argument generation, yet they pose significant risks of manipulation through hallucination and ungrounded persuasion, and often fail to utilize provided factual bases effectively or abstain when arguments are untenable. This paper introduces a novel reflective multi-agent method designed to address these challenges in the context of legally compliant persuasion. Our approach employs specialized agents--a Factor Analyst and an Argument Polisher--in an iterative refinement process to generate 3-ply legal arguments (plaintiff, defendant, rebuttal). We evaluate Reflective Multi-Agent against single-agent, enhanced-prompt single-agent, and non-reflective multi-agent baselines using four diverse LLMs (GPT-4o, GPT-4o-mini, Llama-4-Maverick-17b-128e, Llama-4-Scout-17b-16e) across three legal scenarios: "arguable", "mismatched", and "non-arguable". Results demonstrate Reflective Multi-Agent's significant superiority in successful abstention (preventing generation when arguments cannot be grounded), marked improvements in hallucination accuracy (reducing fabricated and misattributed factors), particularly in "non-arguable" scenarios, and enhanced factor utilization recall (improving the use of provided case facts). These findings suggest that structured reflection within a multi-agent framework offers a robust computable method for fostering ethical persuasion and mitigating manipulation in LLM-based legal argumentation systems, a critical step towards trustworthy AI in law. Project page: https://lizhang-aiandlaw.github.io/A-Reflective-Multi-Agent-Approach-for-Legal-Argument-Generation/
