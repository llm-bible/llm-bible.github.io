---
layout: publication
title: 'PLAY2PROMPT: Zero-shot Tool Instruction Optimization For LLM Agents Via Tool Play'
authors: Wei Fang, Yang Zhang, Kaizhi Qian, James Glass, Yada Zhu
conference: "Arxiv"
year: 2025
bibkey: fang2025zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.14432"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Prompting']
---
Large language models (LLMs) are increasingly integrated with specialized
external tools, yet many tasks demand zero-shot tool usage with minimal or
noisy documentation. Existing solutions rely on manual rewriting or labeled
data for validation, making them inapplicable in true zero-shot settings. To
address these challenges, we propose PLAY2PROMPT, an automated framework that
systematically "plays" with each tool to explore its input-output behaviors.
Through this iterative trial-and-error process, PLAY2PROMPT refines tool
documentation and generates usage examples without any labeled data. These
examples not only guide LLM inference but also serve as validation to further
enhance tool utilization. Extensive experiments on real-world tasks demonstrate
that PLAY2PROMPT significantly improves zero-shot tool performance across both
open and closed models, offering a scalable and effective solution for
domain-specific tool integration.
