---
layout: publication
title: 'Attentive Reasoning Queries: A Systematic Method For Optimizing Instruction-following In Large Language Models'
authors: Bar Karov, Dor Zohar, Yam Marcovitz
conference: "Arxiv"
year: 2025
bibkey: karov2025attentive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.03669'}
tags: ['Reinforcement Learning', 'Agentic', 'Applications', 'Tools']
---
We present Attentive Reasoning Queries (ARQs), a novel structured reasoning
approach that significantly improves instruction-following in Large Language
Models through domain-specialized reasoning blueprints. While LLMs demonstrate
remarkable capabilities across diverse tasks, they often fail to maintain
adherence to complex, use-case-specific instructions during multi-turn
conversations, presenting challenges for business-critical applications. ARQs
address this limitation by guiding LLMs through systematic reasoning steps with
targeted queries that reinstate critical instructions and facilitate
intermediate reasoning throughout the completion process. In extensive testing
within Parlant, our framework for reliable customer-facing agents in which ARQs
were born out of necessity, they achieved a 90.2% success rate across 87 test
scenarios, outperforming both Chain-of-Thought reasoning (86.1%) and direct
response generation (81.5%). ARQs showed particular strength in addressing
persistent failure modes like guideline re-application and hallucination
prevention. Our analysis also revealed that ARQs can potentially be more
computationally efficient than free-form reasoning when carefully designed.
These findings demonstrate that structured reasoning approaches provide
effective mechanisms for controlling how LLMs process information and make
decisions in complex scenarios.
