---
layout: publication
title: Speak It Out&#58; Solving Symbol-related Problems With Symbol-to-language Conversion For Language Models
authors: Wang Yile, Cheng Sijie, Sun Zixin, Li Peng, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: wang2024speak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.11725"}
  - {name: "Code", url: "https://github.com/THUNLP-MT/symbol2language"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Symbols (or more broadly non-natural language textual representations) such as numerical sequences molecular formulas and table delimiters widely exist playing important roles in various tasks such as abstract reasoning chemical property prediction and table question answering. Despite the impressive natural language comprehension capabilities of large language models (LLMs) their reasoning abilities for symbols remain inadequate which could attributed to the difference between symbol representations and general natural languages. We propose symbol-to-language (S2L) a tuning-free method that enables large language models to solve symbol-related problems with information expressed in natural language. Specifically S2L first converts the symbols involved to language-based representations which can be implemented by prompting LLMs or leveraging external tools then these language-based representations are integrated into the original problem via direct substitution or concatenation serving as useful input information for LLMs. We evaluate the S2L method using both API-based (GPT-4 ChatGPT) and open-source (OpenChat) models over eight symbol-related tasks ranging from symbol-only abstract reasoning to sentiment analysis in social media. Experimental results show that S2L consistently leads to superior performance. For example by employing S2L for GPT-4 there can be average significant improvements of +21.937; and +9.537; for subtasks in 1D-ARC and Dyck language respectively. Codes and data are available at https://github.com/THUNLP-MT/symbol2language."
