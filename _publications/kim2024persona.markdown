---
layout: publication
title: 'Persona Is A Double-edged Sword: Mitigating The Negative Impact Of Role-playing Prompts In Zero-shot Reasoning Tasks'
authors: Junseok Kim, Nakyeong Yang, Kyomin Jung
conference: "Arxiv"
year: 2024
bibkey: kim2024persona
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.08631'}
tags: ['Prompting', 'Security', 'Tools', 'Merging']
---
Recent studies demonstrate that prompting a role-playing persona to an LLM
improves reasoning capability. However, assigning an adequate persona is
difficult since LLMs are extremely sensitive to assigned prompts; thus,
inaccurately defined personas sometimes hinder LLMs and degrade their reasoning
capabilities. In this paper, we first investigate the potential negative impact
of injecting persona into language models. Furthermore, we propose a novel
framework, Jekyll \& Hyde, which ensembles the outcomes of both role-playing
and neutral prompts to enhance the robustness of reasoning ability.
Specifically, Jekyll \& Hyde predicts an appropriate persona using an LLM when
defining the role-playing prompt. Then, Jekyll \& Hyde collects two potential
solutions from role-playing and neutral prompts and selects a better solution
using the LLM evaluator. The experimental analysis demonstrates that
role-playing prompts sometimes distract LLMs, degrading their reasoning
abilities in 7 out of 12 datasets in llama3. Meanwhile, Jekyll \& Hyde improve
reasoning capabilities by selecting better choices among the potential
solutions on twelve widely-used natural language reasoning datasets. In
addition, we reveal that assigning LLM-generated personas obtains more stable
results than handcrafted personas.
