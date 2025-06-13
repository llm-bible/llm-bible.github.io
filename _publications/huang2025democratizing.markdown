---
layout: publication
title: 'Manusearch: Democratizing Deep Search In Large Language Models With A Transparent And Open Multi-agent Framework'
authors: Lisheng Huang, Yichen Liu, Jinhao Jiang, Rongxiang Zhang, Jiahao Yan, Junyi Li, Wayne Xin Zhao
conference: "Arxiv"
year: 2025
bibkey: huang2025democratizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18105"}
  - {name: "Code", url: "https://github.com/RUCAIBox/ManuSearch"}
tags: ['Agentic', 'Has Code', 'Model Architecture', 'Tools']
---
Recent advances in web-augmented large language models (LLMs) have exhibited strong performance in complex reasoning tasks, yet these capabilities are mostly locked in proprietary systems with opaque architectures. In this work, we propose \textbf\{ManuSearch\}, a transparent and modular multi-agent framework designed to democratize deep search for LLMs. ManuSearch decomposes the search and reasoning process into three collaborative agents: (1) a solution planning agent that iteratively formulates sub-queries, (2) an Internet search agent that retrieves relevant documents via real-time web search, and (3) a structured webpage reading agent that extracts key evidence from raw web content. To rigorously evaluate deep reasoning abilities, we introduce \textbf\{ORION\}, a challenging benchmark focused on open-web reasoning over long-tail entities, covering both English and Chinese. Experimental results show that ManuSearch substantially outperforms prior open-source baselines and even surpasses leading closed-source systems. Our work paves the way for reproducible, extensible research in open deep search systems. We release the data and code in https://github.com/RUCAIBox/ManuSearch
