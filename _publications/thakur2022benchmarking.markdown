---
layout: publication
title: Benchmarking Large Language Models For Automated Verilog RTL Code Generation
authors: Thakur Shailja, Ahmad Baleegh, Fan Zhenxing, Pearce Hammond, Tan Benjamin, Karri Ramesh, Dolan-gavitt Brendan, Garg Siddharth
conference: "Arxiv"
year: 2022
bibkey: thakur2022benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.11140"}
  - {name: "Code", url: "https://github.com/shailja&#45;thakur/VGen"}
tags: ['Applications', 'Has Code', 'Merging', 'Tools', 'Training Techniques']
---
Automating hardware design could obviate a significant amount of human error from the engineering process and lead to fewer errors. Verilog is a popular hardware description language to model and design digital systems thus generating Verilog code is a critical first step. Emerging large language models (LLMs) are able to write high45;quality code in other programming languages. In this paper we characterize the ability of LLMs to generate useful Verilog. For this we fine45;tune pre45;trained LLMs on Verilog datasets collected from GitHub and Verilog textbooks. We construct an evaluation framework comprising test45;benches for functional analysis and a flow to test the syntax of Verilog code generated in response to problems of varying difficulty. Our findings show that across our problem scenarios the fine45;tuning results in LLMs more capable of producing syntactically correct code (25.937; overall). Further when analyzing functional correctness a fine45;tuned open45;source CodeGen LLM can outperform the state45;of45;the45;art commercial Codex LLM (6.537; overall). Training/evaluation scripts and LLM checkpoints are available https://github.com/shailja&#45;thakur/VGen.
