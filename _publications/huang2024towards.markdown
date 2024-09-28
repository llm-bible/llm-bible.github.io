---
layout: publication
title: Towards Practical Tool Usage for Continually Learning LLMs
authors: Huang Jerry, Parthasarathi Prasanna, Rezagholizadeh Mehdi, Chandar Sarath
conference: "Arxiv"
year: 2024
bibkey: huang2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09339"}
tags: ['Pretraining Methods', 'LLM', 'Arxiv']
---
Large language models (LLMs) show an innate skill for solving language based tasks. But insights have suggested an inability to adjust for information or task-solving skills becoming outdated as their knowledge stored directly within their parameters remains static in time. Tool use helps by offloading work to systems that the LLM can access through an interface but LLMs that use them still must adapt to nonstationary environments for prolonged use as new tools can emerge and existing tools can change. Nevertheless tools require less specialized knowledge therefore we hypothesize they are better suited for continual learning (CL) as they rely less on parametric memory for solving tasks and instead focus on learning when to apply pre-defined tools. To verify this we develop a synthetic benchmark and follow this by aggregating existing NLP tasks to form a more realistic testing scenario. While we demonstrate scaling model size is not a solution regardless of tool usage continual learning techniques can enable tool LLMs to both adapt faster while forgetting less highlighting their potential as continual learners.
