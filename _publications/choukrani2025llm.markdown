---
layout: publication
title: 'LLM-BABYBENCH: Understanding And Evaluating Grounded Planning And Reasoning In Llms'
authors: Omar Choukrani, Idriss Malek, Daniil Orel, Zhuohan Xie, Zangir Iklassov, Martin Takáč, Salem Lahlou
conference: "Arxiv"
year: 2025
bibkey: choukrani2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12135"}
  - {name: "Code", url: "https://github.com/choukrani/llm-babybench}{{GitHub}},"}
  - {name: "Code", url: "https://huggingface.co/datasets/salem-mbzuai/LLM-BabyBench}{{HuggingFace}})"}
tags: ['Agentic', 'Has Code', 'Reinforcement Learning']
---
Assessing the capacity of Large Language Models (LLMs) to plan and reason within the constraints of interactive environments is crucial for developing capable AI agents. We introduce \\(\textbf\{LLM-BabyBench\}\\), a new benchmark suite designed specifically for this purpose. Built upon a textual adaptation of the procedurally generated BabyAI grid world, this suite evaluates LLMs on three fundamental aspects of grounded intelligence: (1) predicting the consequences of actions on the environment state (\\(\textbf\{Predict\}\\) task), (2) generating sequences of low-level actions to achieve specified objectives (\\(\textbf\{Plan\}\\) task), and (3) decomposing high-level instructions into coherent subgoal sequences (\\(\textbf\{Decompose\}\\) task). We detail the methodology for generating the three corresponding datasets (\\(\texttt\{LLM-BabyBench-Predict\}\\), \\(\texttt\{-Plan\}\\), \\(\texttt\{-Decompose\}\\)) by extracting structured information from an expert agent operating within the text-based environment. Furthermore, we provide a standardized evaluation harness and metrics, including environment interaction for validating generated plans, to facilitate reproducible assessment of diverse LLMs. Initial baseline results highlight the challenges posed by these grounded reasoning tasks. The benchmark suite, datasets, data generation code, and evaluation code are made publicly available (\\(\href\{https://github.com/choukrani/llm-babybench\}\{\text\{GitHub\}\}\\), \\(\href\{https://huggingface.co/datasets/salem-mbzuai/LLM-BabyBench\}\{\text\{HuggingFace\}\}\\)).
