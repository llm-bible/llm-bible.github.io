---
layout: publication
title: 'Autopdl: Automatic Prompt Optimization For LLM Agents'
authors: Claudio Spiess, Mandana Vaziri, Louis Mandel, Martin Hirzel
conference: "Arxiv"
year: 2025
bibkey: spiess2025automatic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.04365'}
tags: ['Agentic', 'Few-Shot', 'Efficiency and Optimization', 'Tools', 'Prompting']
---
The performance of large language models (LLMs) depends on how they are
prompted, with choices spanning both the high-level prompting pattern (e.g.,
Zero-Shot, CoT, ReAct, ReWOO) and the specific prompt content (instructions and
few-shot demonstrations). Manually tuning this combination is tedious,
error-prone, and non-transferable across LLMs or tasks. Therefore, this paper
proposes AutoPDL, an automated approach to discover good LLM agent
configurations. Our method frames this as a structured AutoML problem over a
combinatorial space of agentic and non-agentic prompting patterns and
demonstrations, using successive halving to efficiently navigate this space. We
introduce a library implementing common prompting patterns using the PDL prompt
programming language. AutoPDL solutions are human-readable, editable, and
executable PDL programs that use this library. This approach also enables
source-to-source optimization, allowing human-in-the-loop refinement and reuse.
Evaluations across three tasks and six LLMs (ranging from 8B to 70B parameters)
show consistent accuracy gains (\\(9.5\pm17.5\\) percentage points), up to 68.9pp,
and reveal that selected prompting strategies vary across models and tasks.
