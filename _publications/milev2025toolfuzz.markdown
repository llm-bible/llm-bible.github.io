---
layout: publication
title: 'Toolfuzz -- Automated Agent Tool Testing'
authors: Ivan Milev, Mislav Balunović, Maximilian Baader, Martin Vechev
conference: "Arxiv"
year: 2025
bibkey: milev2025toolfuzz
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04479"}
tags: ['Agentic', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Prompting']
---
Large Language Model (LLM) Agents leverage the advanced reasoning
capabilities of LLMs in real-world applications. To interface with an
environment, these agents often rely on tools, such as web search or database
APIs. As the agent provides the LLM with tool documentation along the user
query, the completeness and correctness of this documentation is critical.
However, tool documentation is often over-, under-, or ill-specified, impeding
the agent's accuracy. Standard software testing approaches struggle to identify
these errors as they are expressed in natural language. Thus, despite its
importance, there currently exists no automated method to test the tool
documentation for agents. To address this issue, we present ToolFuzz, the first
method for automated testing of tool documentations. ToolFuzz is designed to
discover two types of errors: (1) user queries leading to tool runtime errors
and (2) user queries that lead to incorrect agent responses. ToolFuzz can
generate a large and diverse set of natural inputs, effectively finding tool
description errors at a low false positive rate. Further, we present two
straightforward prompt-engineering approaches. We evaluate all three tool
testing approaches on 32 common LangChain tools and 35 newly created custom
tools and 2 novel benchmarks to further strengthen the assessment. We find that
many publicly available tools suffer from underspecification. Specifically, we
show that ToolFuzz identifies 20x more erroneous inputs compared to the
prompt-engineering approaches, making it a key component for building reliable
AI agents.
