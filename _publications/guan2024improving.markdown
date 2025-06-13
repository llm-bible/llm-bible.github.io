---
layout: publication
title: 'Contextmodule: Improving Code Completion Via Repository-level Contextual Information'
authors: Zhanming Guan, Junlin Liu, Jierui Liu, Chao Peng, Dexin Liu, Ningyuan Sun, Bo Jiang, Wenchao Li, Jie Liu, Hang Zhu
conference: "Arxiv"
year: 2024
bibkey: guan2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.08063'}
tags: ['Reinforcement Learning', 'RAG', 'Efficiency and Optimization', 'Tools']
---
Large Language Models (LLMs) have demonstrated impressive capabilities in
code completion tasks, where they assist developers by predicting and
generating new code in real-time. However, existing LLM-based code completion
systems primarily rely on the immediate context of the file being edited, often
missing valuable repository-level information, user behaviour and edit history
that could improve suggestion accuracy. Additionally, challenges such as
efficiently retrieving relevant code snippets from large repositories,
incorporating user behavior, and balancing accuracy with low-latency
requirements in production environments remain unresolved. In this paper, we
propose ContextModule, a framework designed to enhance LLM-based code
completion by retrieving and integrating three types of contextual information
from the repository: user behavior-based code, similar code snippets, and
critical symbol definitions. By capturing user interactions across files and
leveraging repository-wide static analysis, ContextModule improves the
relevance and precision of generated code. We implement performance
optimizations, such as index caching, to ensure the system meets the latency
constraints of real-world coding environments. Experimental results and
industrial practise demonstrate that ContextModule significantly improves code
completion accuracy and user acceptance rates.
