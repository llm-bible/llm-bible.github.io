---
layout: publication
title: 'Don''t Take The Premise For Granted: Evaluating The Premise Critique Ability Of Large Language Models'
authors: Jinzhe Li, Gengxu Li, Yi Chang, Yuan Wu
conference: "Arxiv"
year: 2025
bibkey: li2025take
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23715"}
  - {name: "Code", url: "https://github.com/MLGroupJLU/Premise_Critique"}
tags: ['Prompting', 'Security', 'Has Code', 'Tools']
---
Large language models (LLMs) have witnessed rapid advancements, demonstrating remarkable capabilities. However, a notable vulnerability persists: LLMs often uncritically accept flawed or contradictory premises, leading to inefficient reasoning and unreliable outputs. This emphasizes the significance of possessing the \textbf\{Premise Critique Ability\} for LLMs, defined as the capacity to proactively identify and articulate errors in input premises. Most existing studies assess LLMs' reasoning ability in ideal settings, largely ignoring their vulnerabilities when faced with flawed premises. Thus, we introduce the \textbf\{Premise Critique Bench (PCBench)\}, designed by incorporating four error types across three difficulty levels, paired with multi-faceted evaluation metrics. We conducted systematic evaluations of 15 representative LLMs. Our findings reveal: (1) Most models rely heavily on explicit prompts to detect errors, with limited autonomous critique; (2) Premise critique ability depends on question difficulty and error type, with direct contradictions being easier to detect than complex or procedural errors; (3) Reasoning ability does not consistently correlate with the premise critique ability; (4) Flawed premises trigger overthinking in reasoning models, markedly lengthening responses due to repeated attempts at resolving conflicts. These insights underscore the urgent need to enhance LLMs' proactive evaluation of input validity, positioning premise critique as a foundational capability for developing reliable, human-centric systems. The code is available at https://github.com/MLGroupJLU/Premise_Critique.
