---
layout: publication
title: 'Scalemcp: Dynamic And Auto-synchronizing Model Context Protocol Tools For LLM Agents'
authors: Elias Lumer, Anmol Gulati, Vamse Kumar Subbiah, Pradeep Honaganahalli Basavaraju, James A. Burke
conference: "Arxiv"
year: 2025
bibkey: lumer2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.06416"}
tags: ['Agentic', 'RAG', 'Tools']
---
Recent advancements in Large Language Models (LLMs) and the introduction of the Model Context Protocol (MCP) have significantly expanded LLM agents' capability to interact dynamically with external tools and APIs. However, existing tool selection frameworks do not integrate MCP servers, instead relying heavily on error-prone manual updates to monolithic local tool repositories, leading to duplication, inconsistencies, and inefficiencies. Additionally, current approaches abstract tool selection before the LLM agent is invoked, limiting its autonomy and hindering dynamic re-querying capabilities during multi-turn interactions. To address these issues, we introduce ScaleMCP, a novel tool selection approach that dynamically equips LLM agents with a MCP tool retriever, giving agents the autonomy to add tools into their memory, as well as an auto-synchronizing tool storage system pipeline through CRUD (create, read, update, delete) operations with MCP servers as the single source of truth. We also propose a novel embedding strategy, Tool Document Weighted Average (TDWA), designed to selectively emphasize critical components of tool documents (e.g. tool name or synthetic questions) during the embedding process. Comprehensive evaluations conducted on a created dataset of 5,000 financial metric MCP servers, across 10 LLM models, 5 embedding models, and 5 retriever types, demonstrate substantial improvements in tool retrieval and agent invocation performance, emphasizing ScaleMCP's effectiveness in scalable, dynamic tool selection and invocation.
