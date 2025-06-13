---
layout: publication
title: 'OET: Optimization-based Prompt Injection Evaluation Toolkit'
authors: Jinsheng Pan, Xiaogeng Liu, Chaowei Xiao
conference: "Arxiv"
year: 2025
bibkey: pan2025optimization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00843"}
tags: ['Security', 'Efficiency and Optimization', 'Tools', 'RAG', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
natural language understanding and generation, enabling their widespread
adoption across various domains. However, their susceptibility to prompt
injection attacks poses significant security risks, as adversarial inputs can
manipulate model behavior and override intended instructions. Despite numerous
defense strategies, a standardized framework to rigorously evaluate their
effectiveness, especially under adaptive adversarial scenarios, is lacking. To
address this gap, we introduce OET, an optimization-based evaluation toolkit
that systematically benchmarks prompt injection attacks and defenses across
diverse datasets using an adaptive testing framework. Our toolkit features a
modular workflow that facilitates adversarial string generation, dynamic attack
execution, and comprehensive result analysis, offering a unified platform for
assessing adversarial robustness. Crucially, the adaptive testing framework
leverages optimization methods with both white-box and black-box access to
generate worst-case adversarial examples, thereby enabling strict red-teaming
evaluations. Extensive experiments underscore the limitations of current
defense mechanisms, with some models remaining susceptible even after
implementing security enhancements.
