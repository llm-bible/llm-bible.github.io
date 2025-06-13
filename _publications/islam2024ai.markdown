---
layout: publication
title: 'Aivril: Ai-driven RTL Generation With Verification In-the-loop'
authors: Mubashir Ul Islam, Humza Sami, Pierre-emmanuel Gaillardon, Valerio Tenace
conference: "Arxiv"
year: 2024
bibkey: islam2024ai
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.11411'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) are computational models capable of performing
complex natural language processing tasks. Leveraging these capabilities, LLMs
hold the potential to transform the entire hardware design stack, with
predictions suggesting that front-end and back-end tasks could be fully
automated in the near future. Currently, LLMs show great promise in
streamlining Register Transfer Level (RTL) generation, enhancing efficiency,
and accelerating innovation. However, their probabilistic nature makes them
prone to inaccuracies - a significant drawback in RTL design, where reliability
and precision are essential.
  To address these challenges, this paper introduces AIvril, an advanced
framework designed to enhance the accuracy and reliability of RTL-aware LLMs.
AIvril employs a multi-agent, LLM-agnostic system for automatic syntax
correction and functional verification, significantly reducing - and in many
cases, completely eliminating - instances of erroneous code generation.
Experimental results conducted on the VerilogEval-Human dataset show that our
framework improves code quality by nearly 2x when compared to previous works,
while achieving an 88.46% success rate in meeting verification objectives. This
represents a critical step toward automating and optimizing hardware design
workflows, offering a more dependable methodology for AI-driven RTL design.
