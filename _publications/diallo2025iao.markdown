---
layout: publication
title: 'IAO Prompting: Making Knowledge Flow Explicit In Llms Through Structured Reasoning Templates'
authors: Aissatou Diallo, Antonis Bikakis, Luke Dickens, Anthony Hunter, Rob Miller
conference: "Arxiv"
year: 2025
bibkey: diallo2025iao
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.03080'}
tags: ['RAG', 'Applications', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability']
---
While Large Language Models (LLMs) demonstrate impressive reasoning
capabilities, understanding and validating their knowledge utilization remains
challenging. Chain-of-thought (CoT) prompting partially addresses this by
revealing intermediate reasoning steps, but the knowledge flow and application
remain implicit. We introduce IAO (Input-Action-Output) prompting, a structured
template-based method that explicitly models how LLMs access and apply their
knowledge during complex reasoning tasks. IAO decomposes problems into
sequential steps, each clearly identifying the input knowledge being used, the
action being performed, and the resulting output. This structured decomposition
enables us to trace knowledge flow, verify factual consistency, and identify
potential knowledge gaps or misapplications. Through experiments across diverse
reasoning tasks, we demonstrate that IAO not only improves zero-shot
performance but also provides transparency in how LLMs leverage their stored
knowledge. Human evaluation confirms that this structured approach enhances our
ability to verify knowledge utilization and detect potential hallucinations or
reasoning errors. Our findings provide insights into both knowledge
representation within LLMs and methods for more reliable knowledge application.
