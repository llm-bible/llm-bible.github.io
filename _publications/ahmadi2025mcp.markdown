---
layout: publication
title: 'MCP Bridge: A Lightweight, Llm-agnostic Restful Proxy For Model Context Protocol Servers'
authors: Arash Ahmadi, Sarah Sharif, Yaser M. Banad
conference: "Arxiv"
year: 2025
bibkey: ahmadi2025mcp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08999"}
tags: ['Agentic', 'Tools', 'Applications', 'Reinforcement Learning', 'Security']
---
Large Language Models (LLMs) are increasingly augmented with external tools
through standardized interfaces like the Model Context Protocol (MCP). However,
current MCP implementations face critical limitations: they typically require
local process execution through STDIO transports, making them impractical for
resource-constrained environments like mobile devices, web browsers, and edge
computing. We present MCP Bridge, a lightweight RESTful proxy that connects to
multiple MCP servers and exposes their capabilities through a unified API.
Unlike existing solutions, MCP Bridge is fully LLM-agnostic, supporting any
backend regardless of vendor. The system implements a risk-based execution
model with three security levels standard execution, confirmation workflow, and
Docker isolation while maintaining backward compatibility with standard MCP
clients. Complementing this server-side infrastructure is a Python based MCP
Gemini Agent that facilitates natural language interaction with MCP tools. The
evaluation demonstrates that MCP Bridge successfully addresses the constraints
of direct MCP connections while providing enhanced security controls and
cross-platform compatibility, enabling sophisticated LLM-powered applications
in previously inaccessible environments
