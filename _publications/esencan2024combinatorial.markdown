---
layout: publication
title: Combinatorial Reasoning Selecting Reasons in Generative AI Pipelines via Combinatorial Optimization
authors: Esencan Mert, Kumar Tarun Advaith, Asanjan Ata Akbari, Lott P. Aaron, Mohseni Masoud, Unlu Can, Venturelli Davide, Ho Alan
conference: "Arxiv"
year: 2024
bibkey: esencan2024combinatorial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00071"}
tags: ['Efficiency And Optimization', 'Prompting', 'Tools']
---
Recent Large Language Models (LLMs) have demonstrated impressive capabilities at tasks that require human intelligence and are a significant step towards human-like artificial intelligence (AI). Yet the performance of LLMs at reasoning tasks have been subpar and the reasoning capability of LLMs is a matter of significant debate. While it has been shown that the choice of the prompting technique to the LLM can alter its performance on a multitude of tasks including reasoning the best performing techniques require human-made prompts with the knowledge of the tasks at hand. We introduce a framework for what we call Combinatorial Reasoning (CR) a fully-automated prompting method where reasons are sampled from an LLM pipeline and mapped into a Quadratic Unconstrained Binary Optimization (QUBO) problem. The framework investigates whether QUBO solutions can be profitably used to select a useful subset of the reasons to construct a Chain-of-Thought style prompt. We explore the acceleration of CR with specialized solvers. We also investigate the performance of simpler zero-shot strategies such as linear majority rule or random selection of reasons. Our preliminary study indicates that coupling a combinatorial solver to generative AI pipelines is an interesting avenue for AI reasoning and elucidates design principles for future CR methods.
