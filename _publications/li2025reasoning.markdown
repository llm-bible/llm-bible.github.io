---
layout: publication
title: 'Reasoning-as-logic-units: Scaling Test-time Reasoning In Large Language Models Through Logic Unit Alignment'
authors: Cheryl Li, Tianyuan Xu, Yiwen Guo
conference: "Arxiv"
year: 2025
bibkey: li2025reasoning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.07803'}
tags: ['Prompting', 'Interpretability and Explainability', 'Tools']
---
Chain-of-Thought (CoT) prompting has shown promise in enhancing the reasoning
capabilities of large language models (LLMs) by generating natural language
(NL) rationales that lead to the final answer. However, it struggles with
numerical computation, which has somehow led to the development of
program-aided techniques. Despite their potential, a persistent challenge
remains: inconsistencies between LLM-reported reasoning steps and the logic in
generated programs, which we term ``reasoning hallucinations." This stems from
the inherent ambiguities of NL and the statistical nature of LLMs, which often
lack rigorous logical coherence. To address this challenge, we propose a novel
test-time scaling framework, Reasoning-as-Logic-Units (RaLU), which constructs
a more reliable reasoning path by aligning logical units between the generated
program and their corresponding NL descriptions. By decomposing the initially
generated program into discrete units using static analysis, RaLU engages in an
iterative dialogue with the LLM to judge, refine, and explain each unit. A
rewind-and-correct mechanism ensures alignment between code statements and task
requirements in each unit, ultimately forming a cohesive reasoning path under
the program's logic, from which the model reaches a final solution. Our
experiments demonstrate that RaLU significantly outperforms existing baselines
in mathematical reasoning (GSM8K, MATH) and algorithmic reasoning (HumanEval+,
MBPP+), underscoring its potential to advance LLM reasoning and programming by
offering enhanced accuracy and interpretability.
