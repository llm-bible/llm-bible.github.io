---
layout: publication
title: 'Breakpoint: Scalable Evaluation Of System-level Reasoning In LLM Code Agents'
authors: Kaivalya Hariharan, Uzay Girit, Atticus Wang, Jacob Andreas
conference: "Arxiv"
year: 2025
bibkey: hariharan2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00172"}
tags: ['Security', 'Agentic', 'Reinforcement Learning', 'Tools']
---
Benchmarks for large language models (LLMs) have predominantly assessed short-horizon, localized reasoning. Existing long-horizon suites (e.g. SWE-bench) rely on manually curated issues, so expanding or tuning difficulty demands expensive human effort and evaluations quickly saturate. However, many real-world tasks, such as software engineering or scientific research, require agents to rapidly comprehend and manipulate novel, complex structures dynamically; evaluating these capabilities requires the ability to construct large and varied sets of problems for agents to solve. We introduce Breakpoint, a benchmarking methodology that automatically generates code-repair tasks by adversarially corrupting functions within real-world software repositories. Breakpoint systematically controls task difficulty along two clear dimensions: local reasoning (characterized by code complexity metrics such as cyclomatic complexity) and system-level reasoning (characterized by call-graph centrality and the number of simultaneously corrupted interdependent functions). In experiments across more than 900 generated tasks we demonstrate that our methodology can scale to arbitrary difficulty, with state-of-the-art models' success rates ranging from 55% on the easiest tasks down to 0% on the hardest.
