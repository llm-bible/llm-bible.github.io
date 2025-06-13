---
layout: publication
title: 'LLM Agents Should Employ Security Principles'
authors: Kaiyuan Zhang, Zian Su, Pin-yu Chen, Elisa Bertino, Xiangyu Zhang, Ninghui Li
conference: "Arxiv"
year: 2025
bibkey: zhang2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24019"}
tags: ['Agentic', 'Tools', 'Merging', 'Security', 'Prompting']
---
Large Language Model (LLM) agents show considerable promise for automating complex tasks using contextual reasoning; however, interactions involving multiple agents and the system's susceptibility to prompt injection and other forms of context manipulation introduce new vulnerabilities related to privacy leakage and system exploitation. This position paper argues that the well-established design principles in information security, which are commonly referred to as security principles, should be employed when deploying LLM agents at scale. Design principles such as defense-in-depth, least privilege, complete mediation, and psychological acceptability have helped guide the design of mechanisms for securing information systems over the last five decades, and we argue that their explicit and conscientious adoption will help secure agentic systems. To illustrate this approach, we introduce AgentSandbox, a conceptual framework embedding these security principles to provide safeguards throughout an agent's life-cycle. We evaluate with state-of-the-art LLMs along three dimensions: benign utility, attack utility, and attack success rate. AgentSandbox maintains high utility for its intended functions under both benign and adversarial evaluations while substantially mitigating privacy risks. By embedding secure design principles as foundational elements within emerging LLM agent protocols, we aim to promote trustworthy agent ecosystems aligned with user privacy expectations and evolving regulatory requirements.
