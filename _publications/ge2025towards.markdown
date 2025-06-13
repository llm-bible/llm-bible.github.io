---
layout: publication
title: 'Tremu: Towards Neuro-symbolic Temporal Reasoning For Llm-agents With Memory In Multi-session Dialogues'
authors: Yubin Ge, Salvatore Romeo, Jason Cai, Raphael Shu, Monica Sunkara, Yassine Benajiba, Yi Zhang
conference: "Arxiv"
year: 2025
bibkey: ge2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01630"}
tags: ['Agentic', 'GPT', 'Tools', 'Applications', 'Model Architecture', 'Prompting']
---
Temporal reasoning in multi-session dialogues presents a significant
challenge which has been under-studied in previous temporal reasoning
benchmarks. To bridge this gap, we propose a new evaluation task for temporal
reasoning in multi-session dialogues and introduce an approach to construct a
new benchmark by augmenting dialogues from LoCoMo and creating multi-choice
QAs. Furthermore, we present TReMu, a new framework aimed at enhancing the
temporal reasoning capabilities of LLM-agents in this context. Specifically,
the framework employs \textit\{time-aware memorization\} through timeline
summarization, generating retrievable memory by summarizing events in each
dialogue session with their inferred dates. Additionally, we integrate
\textit\{neuro-symbolic temporal reasoning\}, where LLMs generate Python code to
perform temporal calculations and select answers. Experimental evaluations on
popular LLMs demonstrate that our benchmark is challenging, and the proposed
framework significantly improves temporal reasoning performance compared to
baseline methods, raising from 29.83 on GPT-4o via standard prompting to 77.67
via our approach and highlighting its effectiveness in addressing temporal
reasoning in multi-session dialogues.
