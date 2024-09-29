---
layout: publication
title: LLM45;ARC Enhancing Llms With An Automated Reasoning Critic
authors: Kalyanpur Aditya, Saravanakumar Kailash Karthik, Barres Victor, Chu-carroll Jennifer, Melville David, Ferrucci David
conference: "Arxiv"
year: 2024
bibkey: kalyanpur2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17663"}
tags: ['Applications', 'Security', 'Tools', 'Training Techniques']
---
We introduce LLM45;ARC a neuro45;symbolic framework designed to enhance the logical reasoning capabilities of Large Language Models (LLMs) by combining them with an Automated Reasoning Critic (ARC). LLM45;ARC employs an Actor45;Critic method where the LLM Actor generates declarative logic programs along with tests for semantic correctness while the Automated Reasoning Critic evaluates the code runs the tests and provides feedback on test failures for iterative refinement. Implemented using Answer Set Programming (ASP) LLM45;ARC achieves a new state45;of45;the45;art accuracy of 88.3237; on the FOLIO benchmark which tests complex logical reasoning capabilities. Our experiments demonstrate significant improvements over LLM45;only baselines highlighting the importance of logic test generation and iterative self45;refinement. We achieve our best result using a fully automated self45;supervised training loop where the Actor is trained on end45;to45;end dialog traces with Critic feedback. We discuss potential enhancements and provide a detailed error analysis showcasing the robustness and efficacy of LLM45;ARC for complex natural language reasoning tasks.
