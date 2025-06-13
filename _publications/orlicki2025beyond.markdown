---
layout: publication
title: 'Beyond Words: A Latent Memory Approach To Internal Reasoning In Llms'
authors: José I. Orlicki
conference: "Arxiv"
year: 2025
bibkey: orlicki2025beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.21030"}
tags: ['Tools', 'GPT', 'Interpretability and Explainability', 'Model Architecture', 'Training Techniques']
---
Recent advances in large language models (LLMs) have popularized the
chain-of-thought (CoT) paradigm, in which models produce explicit reasoning
steps in natural language. Although this approach improves interpretability and
facilitates external auditing, it may not represent the most computationally
efficient method for internal reasoning. In contrast, human cognition relies on
implicit mental representations that recall past sensory and episodic
information without requiring complete verbalization. In this paper, we propose
a framework that integrates implicit mental representations into the internal
reasoning processes of LLMs. Preliminary experiments indicate that
incorporating an Implicit Memory Module (IMM) into a simple GPT model yields a
reduction of between 35% and 57% in final training loss compared to a regular
GPT baseline. The addition of an explicit interpretability channel (e.g., a
chain-of-thought decoder) is straightforward to implement within this approach.
We outline theoretical foundations, propose technical mechanisms to scale the
memory module, and discuss how these ideas may lead to more efficient and
robust reasoning, with optional future extensions for explicit auditability.
