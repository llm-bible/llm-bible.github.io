---
layout: publication
title: 'RAG-MCP: Mitigating Prompt Bloat In LLM Tool Selection Via Retrieval-augmented Generation'
authors: Tiantian Gan, Qiyao Sun
conference: "Arxiv"
year: 2025
bibkey: gan2025rag
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.03275'}
tags: ['RAG', 'Prompting', 'Tools']
---
Large language models (LLMs) struggle to effectively utilize a growing number
of external tools, such as those defined by the Model Context Protocol
(MCP)\cite\{IntroducingMCP\}, due to prompt bloat and selection complexity. We
introduce RAG-MCP, a Retrieval-Augmented Generation framework that overcomes
this challenge by offloading tool discovery. RAG-MCP uses semantic retrieval to
identify the most relevant MCP(s) for a given query from an external index
before engaging the LLM. Only the selected tool descriptions are passed to the
model, drastically reducing prompt size and simplifying decision-making.
Experiments, including an MCP stress test, demonstrate RAG-MCP significantly
cuts prompt tokens (e.g., by over 50%) and more than triples tool selection
accuracy (43.13% vs 13.62% baseline) on benchmark tasks. RAG-MCP enables
scalable and accurate tool integration for LLMs.
