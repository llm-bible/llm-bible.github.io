---
layout: publication
title: 'Square: Sequential Question Answering Reasoning Engine For Enhanced Chain-of-thought In Large Language Models'
authors: Daniel Fleischer, Moshe Berchansky, Gad Markovits, Moshe Wasserblat
conference: "Arxiv"
year: 2025
bibkey: fleischer2025sequential
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.09390"}
  - {name: "Code", url: "https://github.com/IntelLabs/RAG-FiT/tree/square"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Has Code', 'Prompting']
---
In the rapidly evolving field of Natural Language Processing, Large Language
Models (LLMs) are tasked with increasingly complex reasoning challenges.
Traditional methods like chain-of-thought prompting have shown promise but
often fall short in fully leveraging a model's reasoning capabilities. This
paper introduces SQuARE (Sequential Question Answering Reasoning Engine), a
novel prompting technique designed to improve reasoning through a
self-interrogation paradigm. Building upon CoT frameworks, SQuARE prompts
models to generate and resolve multiple auxiliary questions before tackling the
main query, promoting a more thorough exploration of various aspects of a
topic. Our expansive evaluations, conducted with Llama 3 and GPT-4o models
across multiple question-answering datasets, demonstrate that SQuARE
significantly surpasses traditional CoT prompts and existing
rephrase-and-respond methods. By systematically decomposing queries, SQuARE
advances LLM capabilities in reasoning tasks. The code is publicly available at
https://github.com/IntelLabs/RAG-FiT/tree/square.
