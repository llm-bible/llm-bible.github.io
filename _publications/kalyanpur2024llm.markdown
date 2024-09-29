---
layout: publication
title: LLM-ARC\: Enhancing Llms With An Automated Reasoning Critic
authors: Kalyanpur Aditya, Saravanakumar Kailash Karthik, Barres Victor, Chu-carroll Jennifer, Melville David, Ferrucci David
conference: "Arxiv"
year: 2024
bibkey: kalyanpur2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17663"}
tags: ['Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
We introduce LLM-ARC a neuro-symbolic framework designed to enhance the logical reasoning capabilities of Large Language Models (LLMs) by combining them with an Automated Reasoning Critic (ARC). LLM-ARC employs an Actor-Critic method where the LLM Actor generates declarative logic programs along with tests for semantic correctness while the Automated Reasoning Critic evaluates the code runs the tests and provides feedback on test failures for iterative refinement. Implemented using Answer Set Programming (ASP) LLM-ARC achieves a new state-of-the-art accuracy of 88.3237; on the FOLIO benchmark which tests complex logical reasoning capabilities. Our experiments demonstrate significant improvements over LLM-only baselines highlighting the importance of logic test generation and iterative self-refinement. We achieve our best result using a fully automated self-supervised training loop where the Actor is trained on end-to-end dialog traces with Critic feedback. We discuss potential enhancements and provide a detailed error analysis showcasing the robustness and efficacy of LLM-ARC for complex natural language reasoning tasks.
