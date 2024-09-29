---
layout: publication
title: Toolsandbox A Stateful Conversational Interactive Evaluation Benchmark For LLM Tool Use Capabilities
authors: Lu Jiarui, Holleis Thomas, Zhang Yizhe, Aumayer Bernhard, Nan Feng, Bai Felix, Ma Shuang, Ma Shen, Li Mengyu, Yin Guoli, Wang Zirui, Pang Ruoming
conference: "Arxiv"
year: 2024
bibkey: lu2024interactive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04682"}
  - {name: "Code", url: "https://github.com/apple/ToolSandbox"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Recent large language models (LLMs) advancements sparked a growing research interest in tool assisted LLMs solving real45;world challenges which calls for comprehensive evaluation of tool45;use capabilities. While previous works focused on either evaluating over stateless web services (RESTful API) based on a single turn user prompt or an off45;policy dialog trajectory ToolSandbox includes stateful tool execution implicit state dependencies between tools a built45;in user simulator supporting on45;policy conversational evaluation and a dynamic evaluation strategy for intermediate and final milestones over an arbitrary trajectory. We show that open source and proprietary models have a significant performance gap and complex tasks like State Dependency Canonicalization and Insufficient Information defined in ToolSandbox are challenging even the most capable SOTA LLMs providing brand45;new insights into tool45;use LLM capabilities. ToolSandbox evaluation framework is released at https://github.com/apple/ToolSandbox
