---
layout: publication
title: 'Automated Visualization Code Synthesis Via Multi-path Reasoning And Feedback-driven Optimization'
authors: Wonduk Seo, Seungyong Lee, Daye Kang, Hyunjin An, Zonghao Yuan, Seunghyun Lee
conference: "Arxiv"
year: 2025
bibkey: seo2025automated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11140"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Rapid advancements in Large Language Models (LLMs) have accelerated their integration into automated visualization code generation applications. Despite advancements through few-shot prompting and query expansion, existing methods remain limited in handling ambiguous and complex queries, thereby requiring manual intervention. To overcome these limitations, we propose VisPath: a Multi-Path Reasoning and Feedback-Driven Optimization Framework for Visualization Code Generation. VisPath handles underspecified queries through structured, multi-stage processing. It begins by reformulating the user input via Chain-of-Thought (CoT) prompting, which refers to the initial query while generating multiple extended queries in parallel, enabling the LLM to capture diverse interpretations of the user intent. These queries then generate candidate visualization scripts, which are executed to produce diverse images. By assessing the visual quality and correctness of each output, VisPath generates targeted feedback that is aggregated to synthesize an optimal final result. Extensive experiments on widely-used benchmarks including MatPlotBench and the Qwen-Agent Code Interpreter Benchmark show that VisPath outperforms state-of-the-art methods, offering a more reliable solution for AI-driven visualization code generation.
