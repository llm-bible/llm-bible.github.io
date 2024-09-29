---
layout: publication
title: Loose LIPS Sink Ships&#58; Asking Questions In Battleship With Language-informed Program Sampling
authors: Grand Gabriel, Pepe Valerio, Andreas Jacob, Tenenbaum Joshua B.
conference: "Arxiv"
year: 2024
bibkey: grand2024loose
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.19471"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Questions combine our mastery of language with our remarkable facility for reasoning about uncertainty. How do people navigate vast hypothesis spaces to pose informative questions given limited cognitive resources We study these tradeoffs in a classic grounded question-asking task based on the board game Battleship. Our language-informed program sampling (LIPS) model uses large language models (LLMs) to generate natural language questions translate them into symbolic programs and evaluate their expected information gain. We find that with a surprisingly modest resource budget this simple Monte Carlo optimization strategy yields informative questions that mirror human performance across varied Battleship board scenarios. In contrast LLM-only baselines struggle to ground questions in the board state; notably GPT-4V provides no improvement over non-visual baselines. Our results illustrate how Bayesian models of question-asking can leverage the statistics of language to capture human priors while highlighting some shortcomings of pure LLMs as grounded reasoners.
