---
layout: publication
title: GPT Is Becoming A Turing Machine Here Are Some Ways To Program It
authors: Jojic Ana, Wang Zhen, Jojic Nebojsa
conference: "Arxiv"
year: 2023
bibkey: jojic2023gpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.14310"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Model Architecture', 'Prompting', 'RAG']
---
We demonstrate that through appropriate prompting GPT45;3 family of models can be triggered to perform iterative behaviours necessary to execute (rather than just write or recall) programs that involve loops including several popular algorithms found in computer science curricula or software developer interviews. We trigger execution and description of Iterations by Regimenting Self45;Attention (IRSA) in one (or a combination) of three ways 1) Using strong repetitive structure in an example of an execution path of a target program for one particular input 2) Prompting with fragments of execution paths and 3) Explicitly forbidding (skipping) self45;attention to parts of the generated text. On a dynamic program execution IRSA leads to larger accuracy gains than replacing the model with the much more powerful GPT45;4. IRSA has promising applications in education as the prompts and responses resemble student assignments in data structures and algorithms classes. Our findings hold implications for evaluating LLMs which typically target the in45;context learning We show that prompts that may not even cover one full task example can trigger algorithmic behaviour allowing solving problems previously thought of as hard for LLMs such as logical puzzles. Consequently prompt design plays an even more critical role in LLM performance than previously recognized.
