---
layout: publication
title: 'MCP-RADAR: A Multi-dimensional Benchmark For Evaluating Tool Use Capabilities In Large Language Models'
authors: Xuanqi Gao, Siyi Xie, Juan Zhai, Shqing Ma, Chao Shen
conference: "Arxiv"
year: 2025
bibkey: gao2025mcp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16700"}
  - {name: "Code", url: "https://anonymous.4open.science/r/MCPRadar-B143"}
tags: ['Agentic', 'Efficiency and Optimization', 'Has Code', 'Tools']
---
As Large Language Models (LLMs) evolve from passive text generators to active reasoning agents capable of tool interaction, the Model Context Protocol (MCP) has emerged as a standardized framework for dynamic tool discovery and orchestration. Despite widespread industry adoption, existing evaluation methodologies fail to adequately assess tool utilization capabilities within this new paradigm. This paper introduces MCP-RADAR, the first comprehensive benchmark specifically designed to evaluate LLM performance in the MCP framework through a novel five-dimensional approach measuring: answer accuracy, tool selection efficiency, computational resource efficiency, parameter construction accuracy, and execution speed. Unlike conventional benchmarks that rely on subjective human evaluations or binary success metrics, MCP-RADAR employs objective, quantifiable measurements across multiple task domains including software engineering, mathematical reasoning, and general problem-solving. Our evaluations of leading commercial and open-source LLMs reveal distinctive capability profiles with significant trade-offs between accuracy, efficiency, and speed, challenging traditional single-metric performance rankings. Besides, we provide valuable guidance for developers to optimize their tools for maximum model compatibility and effectiveness. While focused on MCP due to its standardized approach, our methodology remains applicable across all LLM agent tool integration frameworks, providing valuable insights for both LLM developers and tool creators to optimize the entire LLM-tool interaction ecosystem. The implementation, configurations, and datasets used in our evaluation are publicly available at https://anonymous.4open.science/r/MCPRadar-B143.
