---
layout: publication
title: 'MRT At Semeval-2025 Task 8: Maximizing Recovery From Tables With Multiple Steps'
authors: Maximiliano Hormazábal Lagos, Álvaro Bueno Saez, Héctor Cerezo-costas, Pedro Alonso Doval, Jorge Alcalde Vesteiro
conference: "Arxiv"
year: 2025
bibkey: lagos2025mrt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22264"}
tags: ['Prompting', 'RAG', 'Applications']
---
In this paper we expose our approach to solve the \textit\{SemEval 2025 Task 8: Question-Answering over Tabular Data\} challenge. Our strategy leverages Python code generation with LLMs to interact with the table and get the answer to the questions. The process is composed of multiple steps: understanding the content of the table, generating natural language instructions in the form of steps to follow in order to get the answer, translating these instructions to code, running it and handling potential errors or exceptions. These steps use open source LLMs and fine grained optimized prompts for each task (step). With this approach, we achieved a score of \\(70.50%\\) for subtask 1.
