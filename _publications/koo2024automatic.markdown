---
layout: publication
title: "Proptest: Automatic Property Testing For Improved Visual Programming"
authors: Koo Jaywon, Yang Ziyan, Cascante-bonilla Paola, Ray Baishakhi, Ordonez Vicente
conference: "Arxiv"
year: 2024
bibkey: koo2024automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16921"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Visual Programming has recently emerged as an alternative to end-to-end black-box visual reasoning models. This type of method leverages Large Language Models (LLMs) to generate the source code for an executable computer program that solves a given problem. This strategy has the advantage of offering an interpretable reasoning path and does not require finetuning a model with task-specific data. We propose PropTest a general strategy that improves visual programming by further using an LLM to generate code that tests for visual properties in an initial round of proposed solutions. Our method generates tests for data-type consistency output syntax and semantic properties. PropTest achieves comparable results to state-of-the-art methods while using publicly available LLMs. This is demonstrated across different benchmarks on visual question answering and referring expression comprehension. Particularly PropTest improves ViperGPT by obtaining 46.137; accuracy (+6.037;) on GQA using Llama3-8B and 59.537; (+8.137;) on RefCOCO+ using CodeLlama-34B.
