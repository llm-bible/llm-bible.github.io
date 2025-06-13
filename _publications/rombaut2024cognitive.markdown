---
layout: publication
title: 'Watson: A Cognitive Observability Framework For The Reasoning Of Llm-powered Agents'
authors: Benjamin Rombaut, Sogol Masoumzadeh, Kirill Vasilevski, Dayi Lin, Ahmed E. Hassan
conference: "Arxiv"
year: 2024
bibkey: rombaut2024cognitive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.03455'}
tags: ['Agentic', 'Tools', 'Model Architecture']
---
As foundation models (FMs) play an increasingly prominent role in complex
software systems, such as agentic software, they introduce significant
observability and debuggability challenges. Although recent Large Reasoning
Models (LRMs) generate their thought processes as part of the output, in many
scenarios fast-thinking Large Language Models (LLMs) are still preferred due to
latency constraints. LLM-powered agents operate autonomously with opaque
implicit reasoning, making it difficult to debug their unexpected behaviors or
errors. In this paper, we introduce Watson, a novel framework that provides
reasoning observability into the implicit reasoning processes of agents driven
by fast-thinking LLMs, allowing the identification and localization of errors
and guidance for corrections. We demonstrate the accuracy of the recovered
implicit reasoning trace by Watson and its usefulness through debugging and
improving the performance of LLM-powered agents in two scenarios: Massive
Multitask Language Understanding (MMLU) benchmark and SWE-bench-lite. Using
Watson, we were able to observe and identify the implicit reasoning errors, and
automatically provide targeted corrections at runtime that improve the Pass@1
of agents on MMLU and SWE-bench-lite by 7.58 (13.45% relative improvement) and
7.76 (12.31% relative improvement) percentage points, respectively, without
updates to models or the cognitive architecture of the agents.
