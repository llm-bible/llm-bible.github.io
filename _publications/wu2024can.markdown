---
layout: publication
title: 'Can Llms Plan Paths With Extra Hints From Solvers?'
authors: Erik Wu, Sayan Mitra
conference: "Arxiv"
year: 2024
bibkey: wu2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05045"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques', 'Fine-Tuning']
---
Large Language Models (LLMs) have shown remarkable capabilities in natural
language processing, mathematical problem solving, and tasks related to program
synthesis. However, their effectiveness in long-term planning and higher-order
reasoning has been noted to be limited and fragile. This paper explores an
approach for enhancing LLM performance in solving a classical robotic planning
task by integrating solver-generated feedback. We explore four different
strategies for providing feedback, including visual feedback, we utilize
fine-tuning, and we evaluate the performance of three different LLMs across a
10 standard and 100 more randomly generated planning problems. Our results
suggest that the solver-generated feedback improves the LLM's ability to solve
the moderately difficult problems, but the harder problems still remain out of
reach. The study provides detailed analysis of the effects of the different
hinting strategies and the different planning tendencies of the evaluated LLMs.
