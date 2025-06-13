---
layout: publication
title: 'A Proposal For Evaluating The Operational Risk For Chatbots Based On Large Language Models'
authors: Pedro Pinacho-davidson, Fernando Gutierrez, Pablo Zapata, Rodolfo Vergara, Pablo Aqueveque
conference: "Arxiv"
year: 2025
bibkey: pinachodavidson2025proposal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04784"}
tags: ['Agentic', 'Tools', 'Applications', 'RAG', 'Security', 'Prompting']
---
The emergence of Generative AI (Gen AI) and Large Language Models (LLMs) has
enabled more advanced chatbots capable of human-like interactions. However,
these conversational agents introduce a broader set of operational risks that
extend beyond traditional cybersecurity considerations. In this work, we
propose a novel, instrumented risk-assessment metric that simultaneously
evaluates potential threats to three key stakeholders: the service-providing
organization, end users, and third parties. Our approach incorporates the
technical complexity required to induce erroneous behaviors in the
chatbot--ranging from non-induced failures to advanced prompt-injection
attacks--as well as contextual factors such as the target industry, user age
range, and vulnerability severity. To validate our metric, we leverage Garak,
an open-source framework for LLM vulnerability testing. We further enhance
Garak to capture a variety of threat vectors (e.g., misinformation, code
hallucinations, social engineering, and malicious code generation). Our
methodology is demonstrated in a scenario involving chatbots that employ
retrieval-augmented generation (RAG), showing how the aggregated risk scores
guide both short-term mitigation and longer-term improvements in model design
and deployment. The results underscore the importance of multi-dimensional risk
assessments in operationalizing secure, reliable AI-driven conversational
systems.
